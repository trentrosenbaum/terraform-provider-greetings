default: build

# Run acceptance tests
.PHONY: testacc build
testacc:
	TF_ACC=1 go test ./... -v $(TESTARGS) -timeout 120m

build:
    go build -o bin/terrafomr-provider-greetings
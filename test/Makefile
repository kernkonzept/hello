PKGDIR ?= ..
L4DIR  ?= $(PKGDIR)/../..

TEST_GROUP := examples/hello

EXTRA_TEST = hello hello_cfg hello_shared

TEST_TARGET_hello = hello

TEST_TARGET_hello_cfg = hello
MOE_CFG_hello_cfg = simple.cfg

TEST_TARGET_hello_shared = ex_hello_shared

TEST_EXPECTED_hello = hello.output
TEST_EXPECTED_hello_cfg = hello_cfg.output
TEST_EXPECTED_hello_shared = hello_shared.output

include $(L4DIR)/mk/test.mk

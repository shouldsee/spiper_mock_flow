# spiper_mock_flow


### Requirement

- `pip3 install spiper@https://github.com/shouldsee/spiper/tarball/0.0.4`

### Run

```sh
spiper run \
  spiper_mock_flow@https://github.com/shouldsee/spiper_mock_flow/tarball/master \
  spiper_mock_flow:run_and_backup \
  /tmp/test_remote/root 1 2 /tmp/test_remote/root.backup
```


```sh
spiper run \
  spiper_mock_flow@https://github.com/shouldsee/spiper_mock_flow/tarball/master \
  TOPLEVEL:run_and_backup \
  /tmp/test_remote/root 1 2 /tmp/test_remote/root.backup
```

```sh
python3 -m spiper run \
  spiper_mock_flow@https://github.com/shouldsee/spiper_mock_flow/tarball/master \
  TOPLEVEL:run_and_backup \
  /tmp/test_remote/root 1 2 /tmp/test_remote/root.backup
```

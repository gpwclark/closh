1	no support for suspend ctrl+Z
2	unmatched anything results in weird spacing issue,
```
echo "hello
                                                             #_=> "
```
issue is, even if you hit enter after echo "hello<Enter> and ctrl+c out of the
"#___=>" business it  does not save the initial echo "hello in history.
3 nohup firefox-developer-edition t*html &>/dev/null & does not work as expected
4 rm -rf /tmp/*
does not work as expected.
5  vim mode has no motion objects? `ciw` not working, might be a problem with
rebel-readline or some lack of config, need to investigate.

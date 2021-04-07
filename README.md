# yarn-error
Reproduction for a yarn error

This uses yarn branch 2696. Run yarn install in the root repository and it will fail with the following error:

```➤ YN0000: ┌ Link step
➤ YN0062: │ fsevents@patch:fsevents@npm%3A2.3.2#~builtin<compat/fsevents>::version=2.3.2&hash=1cc4b2 The platform win32 is incompatible with this module, link skipped.
➤ YN0001: │ TypeError: Cannot read property 'name' of undefined
    at o (C:\Git\tomotrainerweb\Sources\Web\.yarn\releases\yarn-sources.cjs:440:553)
    at o (C:\Git\tomotrainerweb\Sources\Web\.yarn\releases\yarn-sources.cjs:440:688)
    at o (C:\Git\tomotrainerweb\Sources\Web\.yarn\releases\yarn-sources.cjs:440:688)
    at o (C:\Git\tomotrainerweb\Sources\Web\.yarn\releases\yarn-sources.cjs:440:688)
    at o (C:\Git\tomotrainerweb\Sources\Web\.yarn\releases\yarn-sources.cjs:440:688)
    at kFe (C:\Git\tomotrainerweb\Sources\Web\.yarn\releases\yarn-sources.cjs:440:703)
    at ck (C:\Git\tomotrainerweb\Sources\Web\.yarn\releases\yarn-sources.cjs:440:2166)
    at ck (C:\Git\tomotrainerweb\Sources\Web\.yarn\releases\yarn-sources.cjs:440:2557)
    at rX (C:\Git\tomotrainerweb\Sources\Web\.yarn\releases\yarn-sources.cjs:437:6939)
    at ea (C:\Git\tomotrainerweb\Sources\Web\.yarn\releases\yarn-sources.cjs:445:338)

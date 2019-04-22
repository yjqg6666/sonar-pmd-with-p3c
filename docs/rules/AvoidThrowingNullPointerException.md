
# AvoidThrowingNullPointerException
**Category:** `pmd`<br/>
**Rule Key:** `pmd:AvoidThrowingNullPointerException`<br/>
> :warning: This rule is **deprecated** in favour of [S1695](https://rules.sonarsource.com/java/RSPEC-1695).

-----

Avoid throwing a NullPointerException - it's confusing because most people will assume that the virtual machine threw it. Consider using an IllegalArgumentException instead; this will be clearly seen as a programmer-initiated exception.

<p>
  This rule is deprecated, use {rule:squid:S1695} instead.
</p>

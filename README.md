# alfred-rectangle-quick-command
Send a quick command to Rectangle from Alfred. Use the prefix (`r` by default) followed by the window position and divisor. For example, `r13` places the current window in the first (`1`) third (`3`), while `r46` places it in the fourth (`4`) sixth (`6`). It also supports using letters instead of numbers. Uses the [Rectangle URL Actions](https://github.com/rxhanson/Rectangle?tab=readme-ov-file#execute-an-action-by-url)

## Full list of arguments.
### Half
* Prefixes
  * `1` or `l` for `left-half`
  * `2` or `r` for `right-half`
  * `t` for `top-half`
  * `b` for `bottom-half`
  * `c` for `center-half`
* followed by `2` or `h`

### Third
* Prefixes
  * `1` or `f` for `first-third`
  * `2` or `c` for `center-third`
  * `3` or `l` for `last-third`
* Followed by `3` or `t`

### Fourth
* Prefixes
  * `1` or `f` for `first-fourth`
  * `2` or `s` for `second-fourth`
  * `3` or `t` for `third-fourth`
  * `4` or `l` for `last-fourth`
* Followed by `4` or `f`

### Sixth
* Prefixes
	* `1` or `tl` for `top-left-sixth`
	* `2` or `tc` for `top-center-sixth`
	* `3` or `tr` for `top-right-sixth`
	* `4` or `bl` for `bottom-left-sixth`
	* `5` or `bc` for `bottom-center-sixth`
	* `6` or `br` for `bottom-right-sixth`

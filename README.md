## QQConnent For WHMCS

是NeWorld Team 开源的产品，属于 WHMCS 模块，可在 WHMCS 使用 QQ 登录，并且绑定帐号，显示 QQ 昵称，QQ头像。

调用方式，激活模块，设置参数，赋予权限，查看详细设置，提交按钮。

{$qqlink} 是登录按钮，绑定按钮，解绑按钮，一个按钮多用。

{$avatar} 是头像，{$nickname} 是昵称，例如

```
{if $avatar}
<span class="avatars">
<img src="{$avatar}" alt="{$nickname}" />
{/if}

```

欢迎访问 [https://neworld.org](https://neworld.org)

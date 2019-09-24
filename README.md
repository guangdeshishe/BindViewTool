# BindViewTool
自动生成布局文件里的带id的变量，并且增加BindView注解

使用方法：
1、打开AndroidStudio使用本地安装项目编译生成的插件BindViewTool.jar
2、选中布局文件名称，例如：R.layout.main_activity，则选中『main_activity』即可，或者在弹出的输入框中手动输入『main_activity』
3、解析后会出现弹框，勾选需要生成的变量，添加注释，按需勾选点击事件，点击确定就可以了
生成后的代码示例：
private @BindView(R.id.login_button) @BindClick Button mLoginButton;

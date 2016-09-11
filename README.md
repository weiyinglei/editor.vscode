# editor.vscode
// 将键绑定放入此文件中以覆盖默认值
[
    //ctrl+space被切换输入法快捷键占用
    {
        "key": "ctrl+alt+space",
        "command": "editor.action.triggerSuggest",
        "when": "editorTextFocus"
    },
    // ctrl+d删除一行
    {
        "key": "ctrl+d",
        "command": "editor.action.deleteLines",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+shift+k", //与删除一行的快捷键互换了：）
        "command": "editor.action.addSelectionToNextFindMatch",
        "when": "editorFocus"
    },
    //ctrl+shift+/多行注释
    {
        "key":"ctrl+shift+/",
        "command": "editor.action.blockComment",
        "when": "editorTextFocus"
    }
]

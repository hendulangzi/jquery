# jquery
# [doc](http://www.runoob.com/jquery/jquery-animate.html)
# [layer.layui](http://layer.layui.com/1.8.5/api.html)
# [jQuery实现遮罩层](http://solebillow.com/home/article/detail/id/79.html)
# 复制内容到剪贴板
    <input onclick="oCopy(this)" value="你好.要copy的内容!">
    <script language="javascript">
    function oCopy(obj){
    obj.select();
    document.execCommand("Copy")
    alert("复制成功!");
    }
    </script>

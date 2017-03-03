# svg-demo
前端开发svg动画实例

由UI用AE等作出动画 然后导出svg的json和image文件。
前端利用bodymovin.js执行svg动画

    <div id="svgContainer"></div>
    <script src="bodymovin.js"></script>
    <script type="text/javascript">
      var svgContainer = document.getElementById('svgContainer');
      var animItem = bodymovin.loadAnimation({
          wrapper: svgContainer,
          animType: 'svg',
          loop: true,
          autoplay: true,
          path: 'guard.json'
      });
    </script>
 
 

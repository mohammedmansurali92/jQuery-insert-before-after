# jQuery-insert-before-after
<script>
		$(document).ready(function(){
			$("#btn1").click(function(){
				$("img").before("<b>Hello My</b>");
			})
			$("#btn2").click(function(){
				$("img").after("jQuery");
			})
		})
	</script>
    </head>)
     <body>
    <img src="C:\Users\hp\Desktop\w3jquery.gif" alt="Image jQuery" width="100px" height="100px"><br>
    <button id="btn1">Insert Before</button>
    <button id="btn2">Insert After</button>
   </body>

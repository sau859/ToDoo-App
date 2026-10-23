# ToDoo-App
index html
<!DOCTYPE html>
<html>
<head><title>My Todo</title></head>
<body>
<h2>My Todo List</h2>
<input id="task" placeholder="Task taka">
<button onclick="add()">Add</button>
<ul id="list"></ul>
<script>
function add(){
 let t=document.getElementById('task').value;
 let li=document.createElement('li');
 li.innerText=t;
 document.getElementById('list').appendChild(li);
}
</script>
</body>
</html>
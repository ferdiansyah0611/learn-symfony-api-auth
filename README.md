## Example
```javascript
(async() => {
	var res = await fetch('/api/login_check', {
	    method: 'POST',
	    headers: {
	        'Content-Type': 'application/json'
	    },
	    body: JSON.stringify({
	        username: 'ferdi@gmail.com', password: '11111111'
	    })
	})
	res = await res.json()
	console.log(res)
})()
```
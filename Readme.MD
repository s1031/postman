pm.sendRequest({
    url: "",
    method: 'POST'
}, function(err, res) {
    pm.environment.set("token", res.json().access_token)
})

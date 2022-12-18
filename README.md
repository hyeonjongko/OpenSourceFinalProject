const express = require('express');
const app = express();
app.listen(5000, function() {
    console.log('listening on 5000')
})

app.get('/', function(req, res) {
    res.sendFile(__dirname +'/Road.html')
})
app.get('/Rule', function(req, res) {
    res.sendFile(__dirname +'/Rule.html')
})
app.get('/Convenience', function(req, res) {
    res.sendFile(__dirname +'/Convenience.html')
})
app.get('/Zoo', function(req, res) {
    res.sendFile(__dirname +'/Zoo.html')
})
app.get('/Cafeteria', function(req, res) {
    res.sendFile(__dirname +'/Cafeteria.html')
})
app.get('/Restaurant', function(req, res) {
    res.sendFile(__dirname +'/Restaurant.html')
})
app.get('/Monkey', function(req, res) {
    res.sendFile(__dirname +'/Monkey.html')
})
app.get('/Beast', function(req, res) {
    res.sendFile(__dirname +'/Beast.html')
})
app.get('/Sea', function(req, res) {
    res.sendFile(__dirname +'/Sea.html')
})
app.get('/Herbivores', function(req, res) {
    res.sendFile(__dirname +'/Herbivores.html')
})
app.get('/Child', function(req, res) {
    res.sendFile(__dirname +'/Child.html')
})
app.get('/Bird', function(req, res) {
    res.sendFile(__dirname +'/Bird.html')
})
app.get('/Tropics', function(req, res) {
    res.sendFile(__dirname +'/Tropics.html')
})

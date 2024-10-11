<template>
  <div class="box-container">
    <div class=""></div>
    <div class="big-box1"></div>
    <div class="small-box1"></div>
    <div class="small-box2"></div>
    <div class="small-box3"></div>
    <div class="big-box2"></div>
  </div>
</template>

<style scoped>
.box-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.big-box1 {
  width: 40%;
  height: 200px;
  background-color: brown;
  margin: 10px;
  padding: 20px;
  border: 1px solid #ddd;
}

.big-box2 {
  width: 40%;
  height: 200px;
  background-color: #f0f0f0;
  margin: 10px;
  padding: 20px;
  border: 1px solid #ddd;
}

.small-box {
  width: 20%;
  height: 100px;
  background-color: #f0f0f0;
  margin: 10px;
  padding: 20px;
  border: 1px solid #ddd;
}
</style>
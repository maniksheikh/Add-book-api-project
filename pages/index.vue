<template>
   <div>
    <Headervue></Headervue>
    <nuxt></nuxt>
   </div>
</template>

<script>
import  Headervue  from '../components/Header.vue';
export default {

  components: {
    Headervue
  }
}
</script>

<style>
.container {
  background: #e8e8ec;
  align-items: center;
  justify-content: center;
  width: 1200px;
  margin: auto;
  box-sizing: border-box;
  padding: 0 10px;
  font-family: Arial, Helvetica, sans-serif;
  margin-top: -30px;
  padding: 5px 10px 30px 10px;
  border-radius: 10px;
  margin-top: 5rem;
}
h1 {
  text-align: center;
  align-items: center;
  font-size: 2.3rem;
  font-weight: bold;
  color: #004b63;
}

#book-form {
  font-weight: bold;
  line-height: 1;
  font-size: 1.5rem;
  padding-bottom: 10px;
  color: #2479b3;
}

div {
  margin-top: 10px;
  padding: 5px 0;
}

.u-full-width {
  color: #807a7a !important;
  font-size: 13px;
  font-weight: bold;
}

div input {
  box-sizing: border-box;
  margin-top: 5px;
  border: 1px #96b2c0 solid;
  outline: none;
  border-radius: 7px;
  width: 100%;
  padding: 8px 15px;
  font-size: 14px;
}

.btn {
  font-weight: bold;
  font-size: 1.2rem;
  margin-top: 5px;
  border: 1px #96b2c0 solid;
  background: #68a0b5;
  color: white;
  border-radius: 7px;
  width: 100%;
  padding: 8px;
  cursor: pointer;
}

.table-section {
  width: 100%;
  display: flex;
  justify-content: space-around;
  margin-top:2px;
  border-radius: 15px !important;
}
.table-header {
  padding: 10px 5px !important;
  background: #0c5b75 !important;
  color: white;
}

.table-header th {
   padding: 10px 20px;
}

table {
  width: 100%;
  text-align: center;
  width: 100%;
  height: 100%;
  
}

td {
    padding:5px 20px;
}



tr:nth-child(odd) {
  background: #c0ced3;
}

tr:nth-child(even) {
  background: rgb(223, 217, 217);
}
</style>


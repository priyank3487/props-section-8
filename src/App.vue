<template>
<section>
  <img alt="Vue logo" src="./assets/logo.png">
 <!-- <HelloWorld msg="Welc ome to Your Vue.js App"/> -->
  <h2>my friends</h2>
  </section>
<friend-contact
 name="priyanka saha"
 phone-number="89652347"
 email-address="sahae455@gmail.com"
 is-favourite = "1"
></friend-contact> 
<friend-contact
 name="adelina gomez"
 phone-number="64568522"
 email-address="adelina gomez@gmail.com"
 is-favourite = "0"
></friend-contact> 
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
   data(){
        return{
           
            friends : [
              {
                  id : 'manual',
                  name : 'priyanka saha',
                  phone: '89652347',
                  email : 'sahae455@gmail.com'
              },
               {
                  id : 'manual',
                  name : 'adelina gomez',
                  phone: '64568522',
                  email : 'adelina gomez@gmail.com'
              },
               
            ]

        };
    },

}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

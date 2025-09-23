<script>
    export default { 
        data() {
            return {
                width: '200',
                height: '200',
                myImg: '/assets/me.png'
            }
        },
    }
</script>

<template>

    <!-- add code here -->
     <img v-bind:src="myImg" v-bind:width="width" v-bind:height="height"></img>
     <!-- 
     this works too! without v-bind (':' works as v-bind )
     <img v-bind:src="myImg" :width="width" :height="height"></img>
     : is a short-hand notation of v-bind
     -->
   
</template>

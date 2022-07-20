<template>
    <div class="contain">
    <ul>
        <li>
            <a href="">Home</a>
            <a href="">About us</a>
            <a href="">services</a>
            <a href="">help?</a>
        </li>
    </ul>
    </div>
    <Form />
    <Friend />
    <Friend />

</template>


<script>

import Form from './FormView.vue'
import Friend from './FriendView.vue'

export default{
    components:{
        Form,
        Friend,

     
    }

}
</script>
 

<style>
    .contain{
        display:flex;
        justify-content:center;

    }
    ul {
        text-decoration: none;
        background-color:blue;
        width: 90%;
        list-style: none;
        padding: 15px;
    }
    ul li a{
        color:#ffff;
        text-decoration: none;
        padding-left: 35px;
    }
    input{
        display: flex;
        padding: 10px;
        margin-top: 10px;
    }

</style>
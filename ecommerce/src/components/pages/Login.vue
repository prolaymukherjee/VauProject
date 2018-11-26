<template>
  <div class="login">
    <div class="loginHeader">
      user login
    </div>
       
     <div class="loginContainer">
        <table>
          <tr>
            <td>username</td>
            <td>:</td>
            <td><input type="text" placeholder="username" ></td>
          </tr>

          <tr>
            <td>password</td>
            <td>:</td>
            <td><input type="password" placeholder="password" ></td>
          </tr>

          <tr>
            <td></td>
            <td></td>
            <td><button class="addBtn">Login</button></td>
          </tr>

        </table>
     </div>  
  </div>
  
</template>

<script>
export default {
  name: 'login',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

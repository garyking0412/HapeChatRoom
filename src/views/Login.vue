<template>
  <div class="login">
    <b-jumbotron  header="欢迎使用憨批聊天室"
                  bg-variant="info"
                  text-variant="white">
      <p>如有使用问题请点击下方按钮</p>
      <b-btn target="_blank" href="https://www.baidu.com">寻求帮助</b-btn>
    </b-jumbotron>
    <b-container>
      <b-row>
        <b-col lg="4" md="3"></b-col>
        <b-col lg="4" md="6">
          <LoginForm/>
        </b-col>
        <b-col lg="4" md="3"></b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
import LoginForm from '@/components/LoginForm.vue'


export default {
  name: 'login',
  components: {
    LoginForm
  }
}
</script>

<style>

</style>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
    <script src="https://unpkg.com/vue/dist/vue.js"></script>
  <script src="https://unpkg.com/vue-cookies@1.5.13/vue-cookies.js"></script>
  <title>Welcome</title>
</head>
<body>
  <div id="v-main">

    <p v-if="!ipValue">
      Please enter your ip : <input type="text" @keyup.enter="cloneToken">
    </p>
    <p v-else>
      Is this your ip? {{ ipValue }}
      <button @click="deleteToken">{{deleteIpText}}</button>
      {{deleteIpState}}
    </p>

  </div>
</body>
<script>
  new Vue({
    el:'#v-main',
    data: function() {
      return {
        ipValue: this.$cookies.get('ip'),
        deleteIpText : 'Delete Cookie',
        deleteIpState:''
      }
    },
    methods: {
      cloneToken : function(event){
        this.ipValue = event.target.value;
        const tokenName = 'ackaut';
        const tokenValue = this.$cookies.get(tokenName);

        if (!tokenValue) {
            alert('No token found, please login in some enviroment first.');
            return;
        }
        this.$cookies.set('ip', this.ipValue);
        this.$cookies.set(tokenName, tokenValue, '30d', null, this.ipValue, true);
      },
      deleteToken: function(){
        this.$cookies.remove('ip');
        this.deleteUserState = '√'
        setTimeout(function(){
          location.reload()
        }, 0.5 * 1000)
      }
    }
  })
</script>
</html>

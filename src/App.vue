<template>
  <v-app>
    <v-content>
      <v-row class="hidden-lg-and-up">
        <v-img :src="require('./assets/mobile.jpg')"/>
      </v-row>
      <v-row class="hidden-sm-and-down">
        <v-img :src="require('./assets/web.jpg')"/>
      </v-row>
    </v-content> 
    <v-footer height="auto" width = "100%" class="white pa-3 app--footer">
      <v-card flat tile class="flex text-xs-center">  
        <v-card-text class="pt-0">
          1342, Seongnam-daero, Sujeong-gu, Seongnam-si, Gyeonggi-do, Korea<br/>
          gudokim@telelian.com
        </v-card-text>  
        <v-divider></v-divider>  
        <v-card-text>
          &copy;2018 — <strong>Telelian</strong>
        </v-card-text>
      </v-card>
    </v-footer>   
  </v-app>
</template>

<script>

export default {
  name: 'App',
  components: {
  },
  data () {
    return {
      //
    }
  }
}
</script>

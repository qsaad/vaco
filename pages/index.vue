<template>
  <div>
    <v-row>
      <v-col>
        {{message}}
      </v-col>
    </v-row>
  </div>
</template>

<script>
//import Logo from '~/components/Logo.vue'
//import VuetifyLogo from '~/components/VuetifyLogo.vue'


export default {
  components: {
  
  },//COMPONENTS
  data () {
    return {
      message : 'HELLO WORLD'
    }
  },
  computed:{
    myText(){
      return this.message
    
    }
  }
  }//EXPORT
</script>

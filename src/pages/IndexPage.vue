<template>
  <div class="htmlClass">
    <h1>{{ title }}</h1>
  </div>
  <InputPage></InputPage>
</template>


<script>
import InputPage from './InputPage.vue';
import FunctionPage from '../pages/FunctionPage.vue'

export default {
  name: 'HtmlComponent',
  components:{
    InputPage,
    FunctionPage
},
  data() {
    return {
      title: 'Tipyada',
    }
  },
}
</script>

<style scoped></style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqk_s0y9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:subscript-outline-sharp" /></template>
<style>
.wqk_s0y9m {
  fill: currentColor;
  d: path("M18.385 19v-2.384H21v-.847h-2.616V15h3.385v2.385h-2.615v.846h2.615V19zM7.009 17.384l4.183-6.467L7.354 5h1.284l3.331 5.192h.023L15.375 5h1.29l-3.901 5.917l4.227 6.468H15.7l-3.708-5.714h-.023L8.3 17.385z");
}

</style>

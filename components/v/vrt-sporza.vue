<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="en3gnkbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vrt-sporza" /></template>
<style>
.en3gnkbff {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.2 17.074l4.952-12.542C8.588 10.005 5.495 29.507 19.271 30.188L14.19 42.706C34.36 40.304 45.38 18.77 25.2 17.074");
}

</style>

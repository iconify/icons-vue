<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="c8b1etbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:swap-thin" /></template>
<style>
.c8b1etbxn {
  fill: currentColor;
  d: path("M220 48v104a12 12 0 0 1-12 12H89.66l17.17 17.17a4 4 0 0 1-5.66 5.66l-24-24a4 4 0 0 1 0-5.66l24-24a4 4 0 0 1 5.66 5.66L89.66 156H208a4 4 0 0 0 4-4V48a4 4 0 0 0-4-4H96a4 4 0 0 0-4 4v8a4 4 0 0 1-8 0v-8a12 12 0 0 1 12-12h112a12 12 0 0 1 12 12m-52 148a4 4 0 0 0-4 4v8a4 4 0 0 1-4 4H48a4 4 0 0 1-4-4V104a4 4 0 0 1 4-4h118.34l-17.17 17.17a4 4 0 0 0 5.66 5.66l24-24a4 4 0 0 0 0-5.66l-24-24a4 4 0 0 0-5.66 5.66L166.34 92H48a12 12 0 0 0-12 12v104a12 12 0 0 0 12 12h112a12 12 0 0 0 12-12v-8a4 4 0 0 0-4-4");
}

</style>

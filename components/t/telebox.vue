<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r1g7mcbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:telebox" /></template>
<style>
.r1g7mcbwt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 29.63l-9.75 5.63l-9.75-5.63V18.37l29.25 16.89l9.75-5.63V18.37l-9.75-5.63L24 18.37l19.5 11.26l-29.25-16.89l-9.75 5.63");
}

</style>

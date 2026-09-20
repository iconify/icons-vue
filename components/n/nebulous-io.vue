<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cxlm8n0nx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nebulous-io" /></template>
<style>
.cxlm8n0nx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.182 18.427l.162 15.715m-2.191.951l-13.172-13.45m-8.041 2.619l-1.674 7.932m12.5-17.271a9.423 9.423 0 1 1-18.846 0a9.423 9.423 0 0 1 18.846 0m-8.134 22.403a5.174 5.174 0 0 1-10.348 0a5.174 5.174 0 0 1 10.348 0M41.08 15.282a3.143 3.143 0 0 1-6.287 0a3.143 3.143 0 1 1 6.286 0M40.51 36.53a2.4 2.4 0 1 1-4.8 0a2.4 2.4 0 1 1 4.8 0");
}

</style>

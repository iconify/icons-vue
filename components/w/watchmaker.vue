<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="scfsvuyqo"/><path class="zb7y9nb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:watchmaker" /></template>
<style>
.scfsvuyqo {
  cx: 23.831px;
  cy: 24px;
  r: 13.771px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zb7y9nb7g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.831 14.003V24h-9.997m23.458 2.914h3.97v-5.828H37.29m-5.67-8.441L30.441 4.5h-13.22l-1.179 8.145m0 22.71l1.179 8.145h13.22l1.179-8.145");
}

</style>

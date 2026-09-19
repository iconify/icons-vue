<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rarhph9ay"/><circle class="qad3j2b3z"/><circle class="xxq9vxm1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nt-calculadora" /></template>
<style>
.qad3j2b3z {
  cx: 33.227px;
  cy: 30.265px;
  r: 0.75px;
  fill: currentColor;
}

.rarhph9ay {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.2 0 4 1.8 4 4v29c0 2.2-1.8 4-4 4h-29c-2.2 0-4-1.8-4-4v-29c0-2.2 1.8-4 4-4m19.227 9.926h9m-9 17.831h9m-26.471-3.935l8 7.937m-.039-8l-7.96 7.969m3.999-26.302v9m-4.5-4.5h9");
}

.xxq9vxm1b {
  cx: 33.227px;
  cy: 36.249px;
  r: 0.75px;
  fill: currentColor;
}

</style>

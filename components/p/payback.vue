<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="qmd7beb_v"/><circle class="il8yu-bjp"/><circle class="v9kg4vbxb"/><circle class="ykzpd1b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:payback" /></template>
<style>
.il8yu-bjp {
  cx: 32.438px;
  cy: 16.637px;
  r: 6.975px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qmd7beb_v {
  cx: 15.787px;
  cy: 16.637px;
  r: 6.975px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v9kg4vbxb {
  cx: 15.787px;
  cy: 32.837px;
  r: 6.975px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ykzpd1b_a {
  cx: 32.438px;
  cy: 32.837px;
  r: 6.975px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

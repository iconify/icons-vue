<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="fv763l4rj"/><path class="ohaqbvdwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:prepaidguthaben" /></template>
<style>
.fv763l4rj {
  cx: 29.88px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 13.62px;
  ry: 13.633px;
}

.ohaqbvdwm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.12 37.633A13.626 13.626 0 0 1 4.5 24h0a13.626 13.626 0 0 1 13.62-13.633");
}

</style>

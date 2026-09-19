<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ywaqr3s3g"/><path class="wmk6n1b9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:recharge" /></template>
<style>
.wmk6n1b9w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.97 34.014a10.014 10.014 0 0 1 0-20.028zM8.453 32.672C6.007 30.883 4.5 27.577 4.5 24s1.507-6.883 3.953-8.672z");
}

.ywaqr3s3g {
  cx: 33.486px;
  cy: 24px;
  r: 10.014px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

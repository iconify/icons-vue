<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fffj25btt"/><path class="cn66z92uz"/><circle class="qd88nbcgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:reallybadchess" /></template>
<style>
.cn66z92uz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.58 35.13A36 36 0 0 1 28.42 37a38 38 0 0 1-11-1.69");
}

.fffj25btt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.85 18c-.44 5-2.26 6.74-5.39 7.7S11.5 29 11.5 29l-3.08-5.15S15.06 14 22.51 10.37l.43-5l2.62-.91l3.73 4.86h4.47a58.3 58.3 0 0 1 5.82 25.87v6.39a36 36 0 0 1-11.16 1.92a38.1 38.1 0 0 1-11-1.68V33.5l6.76-8.5");
}

.qd88nbcgs {
  cx: 20.97px;
  cy: 17.53px;
  r: 1.83px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="kw49zdd8l"/><path class="n3wyd_btm"/><path class="mfznn1i5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rakuten-pay" /></template>
<style>
.kw49zdd8l {
  d: path("M12.31 30.552V4h8.873c5.119 0 9.214 3.983 9.214 8.961s-4.095 8.961-9.214 8.961H12.31m9.206-.007l8.54 8.305m-.141 7.69L9.45 41l-5.272-4.687h25.716");
}

.mfznn1i5z {
  d: path("M34.81 41v-7.998h2.6c1.5 0 2.699 1.2 2.699 2.7s-1.2 2.699-2.7 2.699h-2.6");
}

.n3wyd_btm {
  d: path("M43.823 37.001a6.999 6.999 0 1 1-13.997 0a6.999 6.999 0 0 1 13.997 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

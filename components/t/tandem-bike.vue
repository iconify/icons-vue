<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ando42v5o"/><circle class="u5ucynbzi"/><circle class="a6mp61byg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tandem-bike" /></template>
<style>
.a6mp61byg {
  cx: 18.75px;
  cy: 17.25px;
  r: 2.5px;
}

.ando42v5o {
  d: path("m6.12 14.91l1.63-4.41H17l1.12 4.33M7.75 10.5L11 17.25l2-6.75m-5.25 0v-3m-1.25 0H9m4 3v-3m-1.25 0h2.5m2.75 3l-.75-3H18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u5ucynbzi {
  cx: 5.25px;
  cy: 17.25px;
  r: 2.5px;
}

</style>

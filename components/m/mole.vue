<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kw3knabyg"/><circle class="at14pluwe"/><path class="gj5ydolau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mole" /></template>
<style>
.at14pluwe {
  cx: 24px;
  cy: 18.413px;
  r: 0.75px;
  fill: currentColor;
}

.gj5ydolau {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.752 14.115a6.85 6.85 0 0 1 10.496 0M24 23.684v18.973m3.162-11.595h12.122m-31.094 0h12.12m-6.06-6.324v12.648");
}

.kw3knabyg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.503 9.711a13.703 13.703 0 0 1 20.994 0M18.73 17.887a50 50 0 0 0-14.23.527v24.77c5.675-2.187 12.167-1.673 19.5-.527m5.27-24.77a50 50 0 0 1 14.23.527v24.77c-5.674-2.187-12.167-1.673-19.5-.527");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="n08bc9d-z"/><circle class="o5z9hcc9r"/><circle class="eyioeeb6n"/><path class="xr6bcobtf"/></g><path class="ilj_-cl9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:top-news" /></template>
<style>
.eyioeeb6n {
  cx: 22.927px;
  cy: 16.794px;
  r: 1.791px;
}

.ilj_-cl9f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.118 39.533v-9.827l6.511 9.827v-9.827m18.937 0l-2.457 9.827l-2.456-9.827l-2.457 9.827l-2.457-9.827m11.755 8.722c.615.737 1.352 1.105 2.457 1.105h1.474c1.351 0 2.457-1.105 2.457-2.457s-1.106-2.456-2.457-2.456h-1.597c-1.351 0-2.457-1.106-2.457-2.457s1.106-2.457 2.457-2.457h1.474c1.106 0 1.843.246 2.457 1.106M15.844 34.62h3.193m1.72 4.913h-4.913v-9.827h4.913");
}

.n08bc9d-z {
  cx: 22.927px;
  cy: 16.794px;
  r: 8.327px;
}

.o5z9hcc9r {
  cx: 22.927px;
  cy: 16.794px;
  r: 6.585px;
}

.xr6bcobtf {
  d: path("M22.927 12.677a4.117 4.117 0 1 1-3.176 6.738m13.843 4.013V9.985h4.37c2.52 0 4.536 2.017 4.536 4.537s-2.016 4.537-4.537 4.537h-4.369M5.5 9.985h8.738M9.869 23.428V9.985");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

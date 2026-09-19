<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jiy2ld7bl"/><ellipse class="mlojt7b9t"/><ellipse class="wl3i6l8oj"/><circle class="l0trpfyan"/><circle class="c5agnf3ey"/><path class="j3_ckmb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pou" /></template>
<style>
.c5agnf3ey {
  cx: 27.267px;
  cy: 21.139px;
  r: 0.75px;
  fill: currentColor;
}

.j3_ckmb9z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.554 24.367c-1.915 3.38-.789 7.706 3.492 5.453");
}

.jiy2ld7bl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.16 8.489c-2.709-3.165-7.619-3.169-10.332-.007a75 75 0 0 0-8.087 11.427A76.4 76.4 0 0 0 4.89 32.652c-1.38 3.917 1.063 8.155 5.144 8.923a75 75 0 0 0 13.965 1.295a76.4 76.4 0 0 0 13.967-1.304c4.079-.764 6.526-4.995 5.152-8.911a75 75 0 0 0-5.863-12.746A76.4 76.4 0 0 0 29.16 8.49Z");
}

.l0trpfyan {
  cx: 20.663px;
  cy: 21.139px;
  r: 0.75px;
  fill: currentColor;
}

.mlojt7b9t {
  cx: 20.663px;
  cy: 21.139px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.337px;
  ry: 3.971px;
}

.wl3i6l8oj {
  cx: 27.337px;
  cy: 21.139px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.337px;
  ry: 3.971px;
}

</style>

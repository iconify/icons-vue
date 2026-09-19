<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h0k6nn00r"/><ellipse class="fqb1quc5x"/><ellipse class="qe4x9x65l"/><path class="ea98tia8x"/><circle class="uyf50wuco"/><path class="ok0lbhoge"/><circle class="m9zauoysc"/><path class="z3k52ebvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:racoon" /></template>
<style>
.ea98tia8x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.026 28.536c1.35-2.398 1.518-5.388 0-6.815c-1.7-1.595-7.398-1.31-11.046 6.241a14.32 14.32 0 0 0 11.046 8.83");
}

.fqb1quc5x {
  cx: 24px;
  cy: 32.664px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6.212px;
  ry: 4.702px;
}

.h0k6nn00r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 10.848A21.33 21.33 0 0 0 5.202 22.102a5.94 5.94 0 0 0 0 5.601a21.327 21.327 0 0 0 37.596 0a5.94 5.94 0 0 0 0-5.601A21.33 21.33 0 0 0 24 10.848");
}

.m9zauoysc {
  cx: 28.844px;
  cy: 24.144px;
  r: 0.75px;
  fill: currentColor;
}

.ok0lbhoge {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.674 26.653a18 18 0 0 1-1.378-2.281s3.306-4.104 7.637-4.104a4.25 4.25 0 0 1 2.633.763M7.233 19.005C6.025 16.721 5.449 12.19 5.41 9.942a1.01 1.01 0 0 1 1.03-1.036c1.937.039 6.227.539 8.377 4.018m12.157 15.612c-1.35-2.398-1.518-5.388 0-6.815c1.7-1.595 7.398-1.31 11.046 6.241a14.32 14.32 0 0 1-11.046 8.83");
}

.qe4x9x65l {
  cx: 24px;
  cy: 32.258px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.686px;
  ry: 2.033px;
}

.uyf50wuco {
  cx: 19.156px;
  cy: 24.144px;
  r: 0.75px;
  fill: currentColor;
}

.z3k52ebvl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.326 26.653a18 18 0 0 0 1.378-2.281s-3.306-4.104-7.637-4.104a4.25 4.25 0 0 0-2.633.763m12.333-2.026c1.208-2.284 1.784-6.816 1.822-9.063a1.01 1.01 0 0 0-1.028-1.036c-1.937.039-6.227.539-8.377 4.018");
}

</style>

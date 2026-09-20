<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hek95vzlb"/><ellipse class="hev1qfb4y"/><ellipse class="y4iu44tpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:the-souled-store" /></template>
<style>
.hek95vzlb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.212 43.232c1.018-.463 1.887-2.381 3.046-2.09c.85.213 1.903 2.106 3.835 2.12c3.23.026 2.967-4.74 6.647-2.756c2.29 1.234 5.575 1.13 5.62-.934l.544-24.7C37 10.418 30.233 4.174 23.202 4.513c-6.713.324-12.044 5.702-12.088 12.675c-.124 1.45.378 2.252 1.573 2.86c.026-.025.265-1.01.531-2.187l.485-2.142l.113 25.862c.006 1.426 1.694 2.423 3.395 1.65Z");
}

.hev1qfb4y {
  cx: 23.868px;
  cy: 19.264px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.702px;
  ry: 3.776px;
}

.y4iu44tpy {
  cx: 32.294px;
  cy: 19.264px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.096px;
  ry: 3.159px;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="c2hmq65ca"/><circle class="k177doblm"/><path class="nbvinz1wn"/><path class="xvspt7bua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:voyager-for-lemmy-space" /></template>
<style>
.c2hmq65ca {
  cx: 24px;
  cy: 24.694px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 14.336px;
  ry: 8.405px;
}

.k177doblm {
  cx: 24px;
  cy: 36.629px;
  r: 2.038px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nbvinz1wn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.248 32.945l-2.584 1.173m6.181 2.171l-2.069 2.123M27.01 30.84c5.351-.743 8.813-3.396 8.977-5.956M20.99 18.549c-5.35.743-8.813 3.396-8.977 5.956");
}

.xvspt7bua {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 14.608c0-2.913-2.704-5.274-6.039-5.274c-3.049 0-5.563 1.976-5.973 4.54c-2.182-1.252-4.74-1.987-7.488-1.987s-5.306.735-7.488 1.987c-.41-2.564-2.924-4.54-5.973-4.54c-3.335 0-6.039 2.361-6.039 5.274s2.704 5.274 6.039 5.274c.12 0 .236-.01.354-.016a12.6 12.6 0 0 0-1.229 5.41c0 7.396 6.419 13.39 14.336 13.39s14.336-5.994 14.336-13.39a12.6 12.6 0 0 0-1.23-5.41c.119.007.236.016.355.016c3.335 0 6.039-2.361 6.039-5.274m-7.748 18.337l2.584 1.173m-6.181 2.171l2.069 2.123");
}

</style>

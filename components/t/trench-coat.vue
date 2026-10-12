<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="p-h0_9bvx"/><path class="s6zk_ebcm"/><path class="s21nvjoxi"/><path class="i-0w4kbvn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trench-coat" /></template>
<style>
.i-0w4kbvn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.9 13.25h14.2M12 16v5");
}

.p-h0_9bvx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.75h4q1.5 0 2.8.74l.9.52q1.3.74 1.37 2.24l.61 13.5q.07 1.5-1.43 1.5H5.75q-1.5 0-1.43-1.5l.61-13.5Q5 4.75 6.3 4.01l.9-.52q1.3-.74 2.8-.74");
}

.s21nvjoxi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 10.25h.01m3.99 0h.01");
}

.s6zk_ebcm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 3.25L12 8l3.25-4.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

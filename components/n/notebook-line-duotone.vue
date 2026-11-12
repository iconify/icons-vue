<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c-nsjhbdo"/><path class="q1gsu37sn"/><path class="wurlbwzqw"/><path class="kd9g48fun"/><path class="emjwy2umw"/><path class="ur-0t6b4e"/><path class="xxfyb4b_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:notebook-line-duotone" /></template>
<style>
.c-nsjhbdo {
  d: path("M9 22H15C17.8284 22 19.2426 22 20.1213 21.1213C21 20.2426 21 18.8284 21 16V8C21 5.17157 21 3.75736 20.1213 2.87868C19.2426 2 17.8284 2 15 2H9C6.17157 2 4.75736 2 3.87868 2.87868C3 3.75736 3 5.17157 3 8V16C3 18.8284 3 20.2426 3.87868 21.1213C4.75736 22 6.17157 22 9 22Z");
}

.emjwy2umw {
  d: path("M2 8H4");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kd9g48fun {
  d: path("M2 16H4");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.q1gsu37sn {
  d: path("M8 2.5V22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ur-0t6b4e {
  d: path("M11.5 6.5H16.5");
}

.wurlbwzqw {
  d: path("M2 12H4");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.xxfyb4b_r {
  d: path("M11.5 10H16.5");
}

</style>

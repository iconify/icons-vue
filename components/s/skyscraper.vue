<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="zmxzgtp6t"/><path class="e8izmkbix"/><path class="zry7r2bey"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:skyscraper" /></template>
<style>
.e8izmkbix {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 7.75h.01m2.99 0h.01M10.5 14h.01m2.99 0h.01m-3.01 2.75h.01m2.99 0h.01M10.5 19.5h.01m2.99 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zmxzgtp6t {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 20.5v-8.25q0-.75.75-.75H8q.75 0 .75-.75v-5q0-.75.75-.75h5q.75 0 .75.75v5q0 .75.75.75h.25q.75 0 .75.75v8.25q0 .75-.75.75h-8.5q-.75 0-.75-.75");
}

.zry7r2bey {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4.25v-1.5");
}

</style>

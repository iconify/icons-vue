<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cn0sjo9_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:photo-garland" /></template>
<style>
.cn0sjo9_a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4c6 3.5 12.5 3.5 18.5 0M5.75 5.5v3m12.5-3v3M12 6.6v2.9M4.36 8.3l2.78.4q.59.08.51.67l-.64 4.51q-.08.59-.67.51L3.56 14q-.59-.08-.51-.67l.64-4.52q.08-.59.67-.51m6.24 1.2h2.8q.6 0 .6.6v4.55q0 .6-.6.6h-2.8q-.6 0-.6-.6V10.1q0-.6.6-.6m6.26-.8l2.78-.4q.59-.08.67.51l.64 4.52q.08.59-.51.67l-2.78.39q-.59.08-.67-.51l-.64-4.51q-.08-.59.51-.67M4.39 11.74l1.78.25m11.66 0l1.78-.25M11.1 12.9h1.8");
}

</style>

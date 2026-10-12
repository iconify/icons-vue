<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcy6tj8mi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:photo-garland-sharp" /></template>
<style>
.dcy6tj8mi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4c6 3.5 12.5 3.5 18.5 0M5.75 5.5v3m12.5-3v3M12 6.6v2.9M4.36 8.3l2.78.4l.59.08l-.08.59l-.64 4.51l-.08.59l-.59-.08L3.56 14l-.59-.08l.08-.59l.64-4.52l.08-.59zm6.24 1.2H14v5.75h-4V9.5zm6.26-.8l2.78-.4l.59-.08l.08.59l.64 4.52l.08.59l-.59.08l-2.78.39l-.59.08l-.08-.59l-.64-4.51l-.08-.59zM4.39 11.74l1.78.25m11.66 0l1.78-.25M11.1 12.9h1.8");
}

</style>

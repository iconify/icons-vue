<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmqihabsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stylus-sharp" /></template>
<style>
.bmqihabsn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m18.71 4.57l.72.72l1.41 1.41l-1.41 1.41l-5.49 5.49l-1.41 1.41l-1.41-1.41l-.72-.72l-1.41-1.41l1.41-1.41l5.49-5.49l1.41-1.41zM7.93 14.65l1.42 1.42l.53.53l-.69.29l-2.86 1.18l-.69.29l.29-.69l1.18-2.86l.29-.69zm9.02-7.6l-2.48 2.48");
}

</style>

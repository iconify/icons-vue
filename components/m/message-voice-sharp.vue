<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_4iz8dha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:message-voice-sharp" /></template>
<style>
.c_4iz8dha {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.25c4.85 0 8.75 3.5 8.75 7.85s-3.9 7.85-8.75 7.85h-1.616l-1.484-.5L4.6 20l-1.57.523l.67-1.473l1.2-2.9c-1-1.4-1.65-3.15-1.65-5.05c0-4.35 3.9-7.85 8.75-7.85Zm-4.5 7V12m3-3.5v5.25m3-4.5V13m3-2.75V12");
}

</style>

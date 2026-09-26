<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpbd0nb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:terminal-cursor-sharp" /></template>
<style>
.tpbd0nb5y {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 18.9999L12 18.9999M15 4.6997L11.1917 16.2002L8.5317 10.5103L3.9995 8.208L15 4.6997Z");
}

</style>

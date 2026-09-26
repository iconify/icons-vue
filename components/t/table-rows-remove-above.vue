<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwp2m741k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-rows-remove-above" /></template>
<style>
.vwp2m741k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 4.1716C3.8014 4.5954 3 5.7287 3 7L3 19C3 20.6569 4.3431 22 6 22L18 22C19.6569 22 21 20.6569 21 19L21 7C21 5.7287 20.1986 4.5954 19 4.1716M3 13L21 13M9 2L15 8M15 2L9 8");
}

</style>

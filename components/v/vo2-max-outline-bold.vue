<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8-zbnbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:vo2-max-outline-bold" /></template>
<style>
.k8-zbnbse {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
  d: path("M12 3v5m0 0c-4 0 -7 3 -7 7 0 3 1 5 4 5 2 0 3 -1 3 -4 0 3 1 4 3 4 3 0 4 -2 4 -5 0 -4 -3 -7 -7 -7");
}

</style>

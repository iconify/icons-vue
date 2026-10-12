<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1gwl-bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mouth-stick-sharp" /></template>
<style>
.g1gwl-bve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.15 14.75v-2.12l-1.4-1.4V8.95c0-3.4 2.28-6.2 5.2-6.2c2.16 0 3.52 1.4 3.8 3.4l1.12 2.08l.2.52h-1.12v3.6h-2.4v2.4Zm12.54-2.6l2.89.77l1.45.39l-.39 1.45l-1.29 4.83l-.39 1.45l-1.45-.39l-2.89-.77l-1.45-.39l.39-1.45l1.29-4.83l.39-1.45zm-.95 5.45l1.94.52M12.95 10l3.3 3.25");
}

</style>

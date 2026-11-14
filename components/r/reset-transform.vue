<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vpk1fyb2i"/><path class="pqusdii9z"/><path class="is8nqnbzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:reset-transform" /></template>
<style>
.is8nqnbzt {
  d: path("M16.75 14.5L18 15.75L16.75 17");
}

.pqusdii9z {
  d: path("m3 7l8 4.5L19 7m-8 4.5v9m9.75-2A2.75 2.75 0 1 1 18 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vpk1fyb2i {
  d: path("M12.532 19.638L11 20.5L3 16V7l8-4.5L19 7v5.821");
}

</style>

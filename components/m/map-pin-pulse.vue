<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a703ii-sr"/><path class="gual-mbry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:map-pin-pulse" /></template>
<style>
.a703ii-sr {
  d: path("M12 17c-2.5-2-6-5-6-8.5a6 6 0 0 1 12 0c0 3.5-3.5 6.5-6 8.5Z");
}

.gual-mbry {
  d: path("M9.75 8.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM7 15.75a8 3 0 1 0 10 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

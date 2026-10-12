<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gca5v8brc"/><circle class="xhuo7yavf"/><path class="zhbvr361s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:waypoint-sharp" /></template>
<style>
.gca5v8brc {
  d: path("M12 16.25h-.436l-.314-.33C9 13.6 6.5 11.4 6.5 8.75a5.5 5.5 0 0 1 11 0c0 2.65-2.5 4.85-4.75 7.17l-.314.33z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xhuo7yavf {
  cx: 12px;
  cy: 8.75px;
  r: 1.75px;
}

.zhbvr361s {
  d: path("M3.25 20.25h3.5m3.5 0h3.5m3.5 0h3.5");
}

</style>

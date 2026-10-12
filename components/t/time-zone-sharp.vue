<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dldnhmbjp"/><path class="b3j5lwwmp"/><circle class="ygphxfbhc"/><path class="lugpfbc9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:time-zone-sharp" /></template>
<style>
.b3j5lwwmp {
  d: path("M12 2.75C9.6 5.25 8.35 8.35 8.35 12S9.6 18.75 12 21.25M2.75 12H12m0-9.25l2.434 2.586l.816 3.414");
}

.dldnhmbjp {
  d: path("M12 21.25A9.25 9.25 0 1 1 21.25 12");
}

.lugpfbc9h {
  d: path("M17.25 15.5v1.75l1.25.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ygphxfbhc {
  cx: 17.25px;
  cy: 17.25px;
  r: 4px;
}

</style>

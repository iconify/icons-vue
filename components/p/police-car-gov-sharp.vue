<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zm6uqccmb"/><circle class="gsab0-usu"/><circle class="v8hd6uj2s"/><path class="dgai1pbwu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:police-car-gov-sharp" /></template>
<style>
.dgai1pbwu {
  d: path("M10.5 5.25h4v2.5h-4zm-3.75 6.5h12M12.5 8v3.75");
}

.gsab0-usu {
  cx: 6.75px;
  cy: 17.5px;
  r: 2.25px;
}

.v8hd6uj2s {
  cx: 17.25px;
  cy: 17.5px;
  r: 2.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zm6uqccmb {
  d: path("M2.75 16.5v-2.75l-.001-1.184L3.9 12.29l2.6-.64L9 8.45l.615-.769l.985.019h4.15l.904.001l.596.679L19 11.65l1.1.25l1.151.276l-.001 1.184v4.14H19.5a2.25 2.25 0 0 0-4.5 0H9a2.25 2.25 0 0 0-4.5 0H2.75z");
}

</style>

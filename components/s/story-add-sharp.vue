<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wjpiqs1rx"/><circle class="pfpt48slt"/><path class="a0hdtmkuu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:story-add-sharp" /></template>
<style>
.a0hdtmkuu {
  d: path("M12 9.25v5.5M9.25 12h5.5");
}

.pfpt48slt {
  cx: 12px;
  cy: 12px;
  r: 5.5px;
}

.wjpiqs1rx {
  d: path("M17.17 19.67a9.25 9.25 0 0 1-10.34 0m-2.5-2.5a9.25 9.25 0 0 1 0-10.34m2.5-2.5a9.25 9.25 0 0 1 10.34 0m2.5 2.5a9.25 9.25 0 0 1 0 10.34");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

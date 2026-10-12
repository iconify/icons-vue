<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nml8oibyg"/><circle class="bf9_qabtn"/><path class="xaehkvbgh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pickleball-sharp" /></template>
<style>
.bf9_qabtn {
  cx: 17.5px;
  cy: 17.5px;
  r: 3.5px;
}

.nml8oibyg {
  d: path("M3.25 2.75h9.5v11.5h-9.5zm3.25 11.5h3v7h-3z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xaehkvbgh {
  d: path("M16.65 18.35h.01m1.69-1.7h.01");
}

</style>

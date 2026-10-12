<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="mq68zybfy"/><path class="vf8fsqtqf"/><circle class="cri2rlb7x"/><circle class="n5y750rqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-hierarchy-sharp" /></template>
<style>
.cri2rlb7x {
  cx: 6px;
  cy: 18.25px;
  r: 2.5px;
}

.mq68zybfy {
  cx: 12px;
  cy: 5.75px;
  r: 2.5px;
}

.n5y750rqt {
  cx: 18px;
  cy: 18.25px;
  r: 2.5px;
}

.vf8fsqtqf {
  d: path("M12 8.25V12m-6 3.75V12h12v3.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="oar3qcbmz"/><path class="luiokdbcj"/><circle class="d4da7x21x"/><path class="jdgyzzbqi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:permit-sharp" /></template>
<style>
.d4da7x21x {
  cx: 16.75px;
  cy: 16.75px;
  r: 4.5px;
}

.jdgyzzbqi {
  d: path("m14.75 16.75l1.5 1.5l2.75-3");
}

.luiokdbcj {
  d: path("M7.5 9.75v-2.5l2.5-2l2.5 2v2.5Zm0 3.25H14m-6.5 3h3");
}

.oar3qcbmz {
  d: path("M4.25 2.75h13.5v18.5H4.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

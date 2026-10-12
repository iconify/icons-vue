<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="o28budbir"/><path class="fwsp8dbhe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:soldering-iron-sharp" /></template>
<style>
.fwsp8dbhe {
  d: path("m12.09 7.6l2.99-2.99l3.73-1.86l-1.87 3.73l-2.98 2.98Zm-5.03 6.9l-.75.74l-1.486 1.49l1.486 1.49l2.24 2.24");
}

.o28budbir {
  d: path("m12.75 8.26l.55.54l1.59 1.59l-1.59 1.59l-2.79 2.79l-1.59 1.59l-1.59-1.59l-.55-.55l-1.59-1.59l1.59-1.59l2.79-2.78l1.59-1.59z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ty1xtr7vj"/><path class="f2e_s_i9i"/><path class="fwqp77w6k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rainbow-cloud-sharp" /></template>
<style>
.f2e_s_i9i {
  d: path("M5.5 14.5a5.75 5.75 0 0 1 8.88-4.82");
}

.fwqp77w6k {
  d: path("m8.25 14.5l.004-3.982l3.826 1.102");
}

.ty1xtr7vj {
  d: path("M14.4 18a1.88 1.88 0 0 1-.26-3.75a2.7 2.7 0 0 1 5.01-.65a2.12 2.12 0 0 1-.28 4.4ZM2.75 14.5a8.5 8.5 0 0 1 15.2-5.23");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

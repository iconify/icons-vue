<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="iotd-_bjs"/><path class="v9hhmlbli"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:road-sign-sharp" /></template>
<style>
.iotd-_bjs {
  d: path("m13.06 3.81l5.13 5.13L19.25 10l-1.06 1.06l-5.13 5.13L12 17.25l-1.06-1.06l-5.13-5.13L4.75 10l1.06-1.06l5.13-5.13L12 2.75z");
}

.v9hhmlbli {
  d: path("M10 12.5v-3h4.5M13 7.75l1.75 1.75L13 11.25m-1 6v4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

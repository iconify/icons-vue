<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sz2gx2bvd"/><path class="ajkm4g1km"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:octagon-x-duotone" /></template>
<style>
.ajkm4g1km {
  d: path("M9 9L15 15M15 9L9 15");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sz2gx2bvd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14.5645 2C15.4927 2 16.3827 2.36902 17.0391 3.02539L20.9746 6.96094C21.631 7.61731 22 8.50729 22 9.43555V14.5645C22 15.4927 21.631 16.3827 20.9746 17.0391L17.0391 20.9746C16.3827 21.631 15.4927 22 14.5645 22H9.43555C8.50729 22 7.61731 21.631 6.96094 20.9746L3.02539 17.0391C2.36902 16.3827 2 15.4927 2 14.5645V9.43555C2 8.50729 2.36902 7.61731 3.02539 6.96094L6.96094 3.02539C7.61731 2.36902 8.50729 2 9.43555 2H14.5645Z");
  stroke: none;
}

</style>

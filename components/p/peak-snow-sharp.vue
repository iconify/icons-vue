<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="eknilkb-t"/><path class="r-zoitd4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:peak-snow-sharp" /></template>
<style>
.eknilkb-t {
  d: path("m12.6 4.59l8.05 14.57l.6 1.09H2.75l.6-1.09L11.4 4.59L12 3.5z");
}

.r-zoitd4p {
  d: path("m12.36 4.16l3.18 5.78l.36.66l-.57.49l-.51.42l-.57.49l-.59-.46l-1.07-.83l-.59-.46l-.59.46l-1.07.83l-.59.46l-.57-.49l-.51-.42l-.57-.49l.36-.66l3.18-5.78l.36-.66z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

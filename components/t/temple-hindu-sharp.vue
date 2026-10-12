<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="u1a2c4bro"/><path class="bvozojbzs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:temple-hindu-sharp" /></template>
<style>
.bvozojbzs {
  d: path("M12.5 2.75L15.75 4L12.5 5.25ZM9 11.5h6m-4.5 9.75v-4h3v4");
}

.u1a2c4bro {
  d: path("M3.25 21.25V16.5H7v-3c0-3.75 2.25-6.75 5-8.75c2.75 2 5 5 5 8.75v3h3.75v4.75ZM12 4.75v-2");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

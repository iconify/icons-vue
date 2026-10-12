<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mlj6ngb_n"/><path class="kk6b-n2ct"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:swan-sharp" /></template>
<style>
.kk6b-n2ct {
  d: path("M6.48 5.13L3.1 6.4l-.285.107l.1.6L3.2 7l3.05-1l-.001-.466z");
}

.mlj6ngb_n {
  d: path("M9.75 6a1.75 1.75 0 0 0-3.5 0c.5 3-3 5.5-1 8c-1 1.25-.75 6 4.25 6H15c3 0 5.25-2.5 5.25-5.5v-2.25L19.5 10c-2 2.75-5 4-7.75 4h-3c-2-2.5 1.5-5 1-8Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

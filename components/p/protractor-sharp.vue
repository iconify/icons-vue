<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="g-rh5mstr"/><path class="p4qajlb3l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:protractor-sharp" /></template>
<style>
.g-rh5mstr {
  d: path("M2.75 16.25a9.25 9.25 0 0 1 18.5 0v2H2.75v-1Zm9.25-7v2m4.95.05l-1.41 1.41M7.05 11.3l1.41 1.41");
}

.p4qajlb3l {
  d: path("M9.25 18.25v-2a2.75 2.75 0 0 1 5.5 0v2");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

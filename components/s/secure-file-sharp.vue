<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="h8tdg9b9p"/><path class="d2kns2b6u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:secure-file-sharp" /></template>
<style>
.d2kns2b6u {
  d: path("M13 2.75V8h5.5m-11 4h4m-4 3h3m7.42-2.12l2.41.99l.92.38v3.06l-.73.68l-2.79 2.58l-.73.68l-.73-.68l-2.79-2.58l-.73-.68v-3.06l.92-.38l2.41-.99l.92-.38z");
}

.h8tdg9b9p {
  d: path("M6 2.75h7.25L18.5 8v13.25H4V2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

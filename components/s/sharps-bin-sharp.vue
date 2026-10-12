<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wqjvm9b-w"/><path class="t26d8v9pk"/><path class="a9g-5abiq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sharps-bin-sharp" /></template>
<style>
.a9g-5abiq {
  d: path("m12.31 14.01l2.38 3.98l.31.51H9l.31-.51l2.38-3.98l.31-.51zM12 2.75v4");
}

.t26d8v9pk {
  d: path("M6.75 9.75h12l-.13 1.49l-.74 8.52l-.13 1.49H6.25l-.13-1.49l-.74-8.52l-.13-1.49z");
}

.wqjvm9b-w {
  d: path("M3.75 6.75h16.5v3H3.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

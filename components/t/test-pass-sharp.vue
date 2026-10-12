<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dcknlfbcu"/><path class="kin_ijb6z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:test-pass-sharp" /></template>
<style>
.dcknlfbcu {
  d: path("M11 2.75h3.25v6l.56 1.12l5.13 10.26l.56 1.12h-17l.56-1.12L9.19 9.87l.56-1.12v-6z");
}

.kin_ijb6z {
  d: path("m9.25 16.25l2 2l3.75-4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

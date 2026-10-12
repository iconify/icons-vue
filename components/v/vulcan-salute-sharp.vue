<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="detbp0n-c"/><path class="ilvt3kbag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vulcan-salute-sharp" /></template>
<style>
.detbp0n-c {
  d: path("m7.69 20.13l-.63-1.26l-.56-1.12l-.91-.85l-1.93-1.8l-.91-.85l.64-1.07l.22-.36l.64-1.07l.96.8l1.08.9l.96.8l-.41-1.18l-2.43-6.89L4 5l1.17-.45l2.16-.85l1.17-.45l.46 1.16l2.58 6.43L12 12l.46-1.16l2.58-6.43l.46-1.16l1.17.45l2.16.85L20 5l-.24 1.23l-1.77 9.04q-.24 1.23-.73 2.38l-1.02 2.45l-.49 1.15h-7.5z");
}

.ilvt3kbag {
  d: path("m9.5 16.75l2.308 1.154L14.5 16.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

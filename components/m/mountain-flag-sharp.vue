<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="cv3tvbb_a"/><path class="avwy6x7mo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mountain-flag-sharp" /></template>
<style>
.avwy6x7mo {
  d: path("m8.5 16.75l1.25-1l1.25 1l1.25-1l1.25 1M10 9.4V6.25m.47-3.34l4.31 1.43l.47.16l-.47.16l-4.31 1.43l-.47.16v-3.5z");
}

.cv3tvbb_a {
  d: path("M3.28 19.9L9.47 9.85L10 9l.6.8l1.8 2.4l.6.8l.63-.77l.99-1.21l.63-.77l.5.87l5 8.76l.5.87H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

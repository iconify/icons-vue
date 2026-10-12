<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="o5lspzbkw"/><circle class="viz6w_9zv"/><path class="lpsd57b6z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:turnstile-sharp" /></template>
<style>
.lpsd57b6z {
  d: path("M13.5 11.5h7.75m-8.62-1.52l3.75-6.5m-3.75 9.54l3.75 6.5");
}

.o5lspzbkw {
  d: path("M3.5 8.25H10v13H3.5zm2 3H8");
}

.viz6w_9zv {
  cx: 11.75px;
  cy: 11.5px;
  r: 1.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

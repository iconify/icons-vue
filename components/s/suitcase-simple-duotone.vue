<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="s8y_cutte"/><path class="ows-a5bpj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:suitcase-simple-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ows-a5bpj {
  d: path("M216 56h-40v-8a24 24 0 0 0-24-24h-48a24 24 0 0 0-24 24v8H40a16 16 0 0 0-16 16v128a16 16 0 0 0 16 16h176a16 16 0 0 0 16-16V72a16 16 0 0 0-16-16M96 48a8 8 0 0 1 8-8h48a8 8 0 0 1 8 8v8H96Zm120 24v72H40V72Zm0 128H40v-40h176z");
}

.s8y_cutte {
  d: path("M224 152v48a8 8 0 0 1-8 8H40a8 8 0 0 1-8-8v-48Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

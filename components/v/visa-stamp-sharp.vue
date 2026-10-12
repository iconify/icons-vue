<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="szh5qkv1w"/><path class="u3jnvdtgb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:visa-stamp-sharp" /></template>
<style>
.szh5qkv1w {
  d: path("M4.75 2.75h14.5v18.5H4.75zm3.5 3.75h7.5m-7.5 2.75h4.5");
}

.u3jnvdtgb {
  d: path("m8.11 13.15l6.91-1.22l.98-.17l.17.98l.53 2.96l.17.98l-.98.17l-6.91 1.22l-.98.17l-.17-.98l-.53-2.96l-.17-.98zm1.64 2.35l4.25-.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_xr9egzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:plumb-bob" /></template>
<style>
.u_xr9egzp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75v5.5m-2.5-5.5h5M9 8.25h6a1 1 0 0 1 1 1v1.5a1 1 0 0 1-.25.65l-3 9.1a.8.8 0 0 1-1.5 0l-3-9.1a1 1 0 0 1-.25-.65v-1.5a1 1 0 0 1 1-1m-1 3h8");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dm7khd2qi"/><path class="bv9e6zm4f"/><path class="soxjx-b_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pakistan-crescent-flag-star-sharp" /></template>
<style>
.bv9e6zm4f {
  d: path("M16.5 7.13a3.5 3.5 0 1 0 0 6.24a3.25 3.25 0 0 1 0-6.24Z");
}

.dm7khd2qi {
  d: path("M3 2.75v18.5M5.5 4h15.75v12.5H5.5zM9 4v12.5");
}

.soxjx-b_k {
  d: path("m18 7.63l.21.47l.1.23l.25.03l.52.05l.25.03l-.19.16l-.39.35l-.18.17l.05.24l.11.51l.05.24l-.21-.12l-.45-.26l-.22-.13l-.22.13l-.45.26l-.21.12l.05-.24l.11-.51l.05-.24l-.18-.17l-.39-.35l-.19-.16l.25-.03l.52-.05l.25-.03l.1-.23l.21-.47l.1-.23z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

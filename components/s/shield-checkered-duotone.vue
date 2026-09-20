<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="k9589jyde"/><path class="yo088lcno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:shield-checkered-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k9589jyde {
  d: path("M128 48v80H40.87a146 146 0 0 1-.87-16V56a8 8 0 0 1 8-8Zm0 80v104s78.06-21.3 87.13-104Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yo088lcno {
  d: path("M208 40H48a16 16 0 0 0-16 16v56c0 52.72 25.52 84.67 46.93 102.19c23.06 18.86 46 25.27 47 25.53a8 8 0 0 0 4.2 0c1-.26 23.91-6.67 47-25.53C198.48 196.67 224 164.72 224 112V56a16 16 0 0 0-16-16m-88 180.55a131 131 0 0 1-30.93-18.74c-21.15-17.3-34.2-39.37-39-65.81H120ZM120 120H48.23c-.15-2.63-.23-5.29-.23-8V56h72Zm47.4 81.42a131.3 131.3 0 0 1-31.4 19.11V136h69.91c-4.75 26.24-17.64 48.18-38.51 65.42M208 112c0 2.71-.08 5.37-.23 8H136V56h72Z");
}

</style>

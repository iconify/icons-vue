<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="f8zg4-n7g"/><path class="gc_x9w5-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:poker-chip-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f8zg4-n7g {
  d: path("M128 32a96 96 0 1 0 96 96a96 96 0 0 0-96-96m0 152a56 56 0 1 1 56-56a56 56 0 0 1-56 56");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gc_x9w5-o {
  d: path("M128 24a104 104 0 1 0 104 104A104.11 104.11 0 0 0 128 24m0 152a48 48 0 1 1 48-48a48.05 48.05 0 0 1-48 48m39.21-98.53a63.66 63.66 0 0 0-31.21-13v-24.1a87.6 87.6 0 0 1 48.28 20ZM120 64.52a63.66 63.66 0 0 0-31.21 13L71.72 60.4a87.6 87.6 0 0 1 48.28-20ZM77.47 88.79a63.66 63.66 0 0 0-13 31.21h-24.1a87.6 87.6 0 0 1 20-48.28ZM64.52 136a63.66 63.66 0 0 0 13 31.21L60.4 184.28a87.6 87.6 0 0 1-20-48.28Zm24.27 42.53A63.66 63.66 0 0 0 120 191.48v24.15a87.6 87.6 0 0 1-48.28-20ZM136 191.48a63.66 63.66 0 0 0 31.21-12.95l17.07 17.07a87.6 87.6 0 0 1-48.28 20Zm42.53-24.27A63.66 63.66 0 0 0 191.48 136h24.15a87.6 87.6 0 0 1-20 48.28ZM191.48 120a63.66 63.66 0 0 0-12.95-31.21l17.07-17.07a87.6 87.6 0 0 1 20 48.28Z");
}

</style>

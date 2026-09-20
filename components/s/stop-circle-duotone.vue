<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="fo_gmx7hd"/><path class="o_5x9tkbo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:stop-circle-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fo_gmx7hd {
  d: path("M128 32a96 96 0 1 0 96 96a96 96 0 0 0-96-96m32 128H96V96h64Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o_5x9tkbo {
  d: path("M128 24a104 104 0 1 0 104 104A104.11 104.11 0 0 0 128 24m0 192a88 88 0 1 1 88-88a88.1 88.1 0 0 1-88 88m32-128H96a8 8 0 0 0-8 8v64a8 8 0 0 0 8 8h64a8 8 0 0 0 8-8V96a8 8 0 0 0-8-8m-8 64h-48v-48h48Z");
}

</style>

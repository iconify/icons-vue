<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="m6e5leb2r"/><path class="s7gw07b8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:steps-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.m6e5leb2r {
  d: path("M240 56v128a16 16 0 0 1-16 16H72v-48h56v-48h56V56Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s7gw07b8f {
  d: path("M248 56a8 8 0 0 1-8 8h-48v40a8 8 0 0 1-8 8h-48v40a8 8 0 0 1-8 8H80v40a8 8 0 0 1-8 8H16a8 8 0 0 1 0-16h48v-40a8 8 0 0 1 8-8h48v-40a8 8 0 0 1 8-8h48V56a8 8 0 0 1 8-8h56a8 8 0 0 1 8 8");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="cnybtlipb"/><path class="xxx8ahb7w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:seat-duotone" /></template>
<style>
.cnybtlipb {
  d: path("M216 160v32a8 8 0 0 1-8 8h-93.89a8 8 0 0 1-7.15-4.42l-58.12-116a8 8 0 0 1 0-7.16l22.16-44a8 8 0 0 1 10.73-3.57l33.89 14.31a8 8 0 0 1 3.57 10.73l-14.35 26.53a8 8 0 0 0 0 7.16l31.78 64a8 8 0 0 0 7.16 4.42H208a8 8 0 0 1 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cuyn6tgcc {
  fill: currentColor;
}

.xxx8ahb7w {
  d: path("M224 232a8 8 0 0 1-8 8H112a8 8 0 0 1 0-16h104a8 8 0 0 1 8 8m0-72v32a16 16 0 0 1-16 16h-93.89a15.93 15.93 0 0 1-14.32-8.85l-58.11-116a16.1 16.1 0 0 1 0-14.32l22.12-44A16 16 0 0 1 85 17.56l33.69 14.22l.47.22a16 16 0 0 1 7.15 21.46a1.5 1.5 0 0 1-.11.22L112 80l31.78 64H208a16 16 0 0 1 16 16m-16 0h-64.23a15.91 15.91 0 0 1-14.31-8.85l-31.79-64a16.07 16.07 0 0 1 0-14.29l.12-.22L112 46.32L78.57 32.21c-.16-.06-.31-.14-.46-.21L56 76l58.1 116H208Z");
}

</style>

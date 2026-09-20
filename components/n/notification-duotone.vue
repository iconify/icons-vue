<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="jexk-ntdg"/><path class="d1xfpncjy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:notification-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d1xfpncjy {
  d: path("M216 128v80a16 16 0 0 1-16 16H48a16 16 0 0 1-16-16V56a16 16 0 0 1 16-16h80a8 8 0 0 1 0 16H48v152h152v-80a8 8 0 0 1 16 0m16-68a36 36 0 1 1-36-36a36 36 0 0 1 36 36m-16 0a20 20 0 1 0-20 20a20 20 0 0 0 20-20");
}

.jexk-ntdg {
  d: path("M224 60a28 28 0 1 1-28-28a28 28 0 0 1 28 28");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

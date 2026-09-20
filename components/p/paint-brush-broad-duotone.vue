<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="oeiukwbkh"/><path class="sx08c3thh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:paint-brush-broad-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.oeiukwbkh {
  d: path("M216 112v24a16 16 0 0 1-16 16h-48a8 8 0 0 0-7.92 9.13L152 208a24 24 0 0 1-48 0l7.92-46.87A8 8 0 0 0 104 152H56a16 16 0 0 1-16-16v-24Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sx08c3thh {
  d: path("M216 24H72a40 40 0 0 0-40 40v72a24 24 0 0 0 24 24h48l-7.89 46.67A8.4 8.4 0 0 0 96 208a32 32 0 0 0 64 0a8.4 8.4 0 0 0-.11-1.33L152 160h48a24 24 0 0 0 24-24V32a8 8 0 0 0-8-8M72 40h104v40a8 8 0 0 0 16 0V40h16v64H48V64a24 24 0 0 1 24-24m128 104h-48a16 16 0 0 0-15.84 18.26v.2L144 208.6a16 16 0 0 1-32 0l7.8-46.14v-.2A16 16 0 0 0 104 144H56a8 8 0 0 1-8-8v-16h160v16a8 8 0 0 1-8 8");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="wjbcr2bed"/><path class="jef7mubbk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:tree-evergreen-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jef7mubbk {
  d: path("M230.31 187.09L184.36 128H208a8 8 0 0 0 6.34-12.88l-80-104a8 8 0 0 0-12.68 0l-80 104A8 8 0 0 0 48 128h23.64l-45.95 59.09A8 8 0 0 0 32 200h88v40a8 8 0 0 0 16 0v-40h88a8 8 0 0 0 6.31-12.91M48.36 184l46-59.09A8 8 0 0 0 88 112H64.25L128 29.12L191.75 112H168a8 8 0 0 0-6.31 12.91L207.64 184Z");
}

.wjbcr2bed {
  d: path("m32 192l56-72H48l80-104l80 104h-40l56 72Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="iyxdrpblc"/><path class="ipu0dvp_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:video-camera-slash-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ipu0dvp_o {
  d: path("M251.77 73a8 8 0 0 0-8.21.39L208 97.05V72a16 16 0 0 0-16-16h-78.94a8 8 0 0 0 0 16H192v87.63a8 8 0 0 0 16 0V159l35.56 23.71A8 8 0 0 0 248 184a8 8 0 0 0 8-8V80a8 8 0 0 0-4.23-7M240 161.05l-32-21.33v-23.44L240 95ZM53.92 34.62a8 8 0 1 0-11.84 10.76L51.73 56H32a16 16 0 0 0-16 16v112a16 16 0 0 0 16 16h150.64l19.44 21.38a8 8 0 1 0 11.84-10.76ZM32 184V72h34.28L168.1 184Z");
}

.iyxdrpblc {
  d: path("M200 72v112a8 8 0 0 1-8 8H32a8 8 0 0 1-8-8V72a8 8 0 0 1 8-8h160a8 8 0 0 1 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

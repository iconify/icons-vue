<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="w9yal4bar"/><path class="f6k2f9btx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:signpost-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f6k2f9btx {
  d: path("M246 106.65L212.33 69.3a16 16 0 0 0-11.89-5.3H136V32a8 8 0 0 0-16 0v32H40a16 16 0 0 0-16 16v64a16 16 0 0 0 16 16h80v64a8 8 0 0 0 16 0v-64h64.44a16 16 0 0 0 11.89-5.3L246 117.35a8 8 0 0 0 0-10.7M200.44 144H40V80h160.44l28.8 32Z");
}

.w9yal4bar {
  d: path("m240 112l-33.62 37.35a8 8 0 0 1-5.94 2.65H40a8 8 0 0 1-8-8V80a8 8 0 0 1 8-8h160.44a8 8 0 0 1 5.94 2.65Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

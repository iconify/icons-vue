<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dw94pac9p"/><path class="uzrt0fbtk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:play-pause-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dw94pac9p {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m3.514 5.143l10 6a.997.997 0 0 1 0 1.714l-10 6A.997.997 0 0 1 2 18V6a1 1 0 0 1 1.514-.857");
}

.uzrt0fbtk {
  d: path("M18 6v12a1 1 0 0 1-2 0V6a1 1 0 0 1 2 0m4 0v12a1 1 0 0 1-2 0V6a1 1 0 0 1 2 0");
}

</style>

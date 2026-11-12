<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y32qgqgwi"/><path class="q0l2hqbjk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:upscale-sparkle-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.q0l2hqbjk {
  d: path("m2.986 5l.003-.001c.134-.028.261-.107.375-.177a4.9 4.9 0 0 0 1.458-1.458c.07-.114.149-.241.177-.375L5 2.986a1 1 0 0 1 2 0l.001.003c.028.134.107.261.177.375a4.9 4.9 0 0 0 1.458 1.458c.114.07.241.149.375.177L9.014 5a1 1 0 0 1 0 2l-.003.001c-.134.028-.261.107-.375.177a4.9 4.9 0 0 0-1.458 1.458c-.07.114-.149.241-.177.375L7 9.014a1 1 0 0 1-2 0l-.001-.003c-.028-.134-.107-.261-.177-.375a4.9 4.9 0 0 0-1.458-1.458c-.114-.07-.241-.149-.375-.177L2.986 7a1 1 0 0 1 0-2m10.307 4.293L17.586 5H16a1 1 0 0 1 0-2h4a1 1 0 0 1 1 1v4a1 1 0 0 1-2 0V6.414l-4.293 4.293a.999.999 0 1 1-1.414-1.414");
}

.y32qgqgwi {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 15a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3v4a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>

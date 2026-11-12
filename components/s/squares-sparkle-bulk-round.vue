<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tnir2kbph"/><path class="h5qieedns"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:squares-sparkle-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.h5qieedns {
  d: path("m14.986 5l.003-.001c.134-.028.261-.107.375-.177a4.9 4.9 0 0 0 1.458-1.458c.07-.114.149-.241.177-.375L17 2.986a1 1 0 0 1 2 0l.001.003c.028.134.107.261.177.375a4.9 4.9 0 0 0 1.458 1.458c.114.07.241.149.375.177l.003.001a1 1 0 0 1 0 2l-.003.001c-.134.028-.261.107-.375.177a4.9 4.9 0 0 0-1.458 1.458c-.07.114-.149.241-.177.375L19 9.014a1 1 0 0 1-2 0l-.001-.003c-.028-.134-.107-.261-.177-.375a4.9 4.9 0 0 0-1.458-1.458c-.114-.07-.241-.149-.375-.177L14.986 7a1 1 0 0 1 0-2");
}

.tnir2kbph {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm0 12a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm12 0a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3Z");
}

</style>

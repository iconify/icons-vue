<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="olcahyb3y"/><path class="sigku1bfr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:music-note-sparkle-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.olcahyb3y {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 17a4 4 0 1 1 8 0a4 4 0 0 1-8 0");
}

.sigku1bfr {
  d: path("M9 4a1 1 0 0 1 1.447-.894l6 3a1 1 0 1 1-.894 1.788L11 5.618V17a1 1 0 0 1-2 0Zm4.989 8.999c.134-.028.261-.107.375-.177a4.9 4.9 0 0 0 1.458-1.458c.07-.114.149-.241.177-.375l.001-.003a1 1 0 0 1 2 0l.001.003c.028.134.107.261.177.375a4.9 4.9 0 0 0 1.458 1.458c.114.07.241.149.375.177l.003.001a1 1 0 0 1 0 2l-.003.001c-.134.028-.261.107-.375.177a4.9 4.9 0 0 0-1.458 1.458c-.07.114-.149.241-.177.375l-.001.003a1 1 0 0 1-2 0l-.001-.003c-.028-.134-.107-.261-.177-.375a4.9 4.9 0 0 0-1.458-1.458c-.114-.07-.241-.149-.375-.177L13.986 15a1 1 0 0 1 0-2Z");
}

</style>

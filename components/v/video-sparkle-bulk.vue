<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="s5nt3bc_v"/><path class="xnmszjbnx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:video-sparkle-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.s5nt3bc_v {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 8a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

.xnmszjbnx {
  d: path("M18.553 7.106c.356-.181.75-.274 1.149-.273C20.924 6.836 22 7.735 22 9v6c0 1.265-1.076 2.164-2.298 2.167a2.5 2.5 0 0 1-1.149-.273l-4-2a1 1 0 1 1 .894-1.788l4 2a.6.6 0 0 0 .251.061c.093 0 .302-.044.302-.167V9c0-.123-.209-.167-.302-.167a.6.6 0 0 0-.251.061l-4 2a1 1 0 1 1-.894-1.788ZM5.989 10.999c.134-.028.261-.107.375-.177a4.9 4.9 0 0 0 1.458-1.458c.07-.114.149-.241.177-.375L8 8.986a1 1 0 0 1 2 0l.001.003c.028.134.107.261.177.375a4.9 4.9 0 0 0 1.458 1.458c.114.07.241.149.375.177l.003.001a1 1 0 0 1 0 2l-.003.001c-.134.028-.261.107-.375.177a4.9 4.9 0 0 0-1.458 1.458c-.07.114-.149.241-.177.375l-.001.003a1 1 0 0 1-2 0l-.001-.003c-.028-.134-.107-.261-.177-.375a4.9 4.9 0 0 0-1.458-1.458c-.114-.07-.241-.149-.375-.177L5.986 13a1 1 0 0 1 0-2Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="tfsu_mg8j"/><path class="hdf52db7a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:paint-brush-household-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hdf52db7a {
  d: path("M230.64 25.36a32 32 0 0 0-45.26 0q-.21.21-.42.45l-53.41 62.41L121 77.64a24 24 0 0 0-33.95 0l-76.69 76.7a8 8 0 0 0 0 11.31l80 80a8 8 0 0 0 11.31 0L178.36 169a24 24 0 0 0 0-33.95l-10.58-10.57L230.19 71c.15-.14.31-.28.45-.43a32 32 0 0 0 0-45.21M96 228.69L79.32 212l22.34-22.35a8 8 0 0 0-11.31-11.31L68 200.68L55.32 188l22.34-22.35a8 8 0 0 0-11.31-11.31L44 176.68L27.31 160L72 115.31L140.69 184ZM219.52 59.1l-68.71 58.81a8 8 0 0 0-.46 11.74L167 146.34a8 8 0 0 1 0 11.31l-15 15L83.32 104l15-15a8 8 0 0 1 11.31 0l16.69 16.69a8 8 0 0 0 11.74-.46l58.84-68.75a16 16 0 0 1 22.62 22.62");
}

.tfsu_mg8j {
  d: path("m225 65l-69 59l16.69 16.69a16 16 0 0 1 0 22.62L152 184l-80-80l20.69-20.69a16 16 0 0 1 22.62 0L132 100l59-69a24 24 0 0 1 34 34");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

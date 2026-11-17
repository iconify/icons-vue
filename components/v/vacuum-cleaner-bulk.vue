<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="t5t8b5byf"/><path class="e7ghflo5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:vacuum-cleaner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.e7ghflo5a {
  d: path("M6 8c0-2.35 1.681-4.087 3.9-4.599c.965-.223 2.006-.204 2.938.148c.991.375 1.772 1.12 2.111 2.135L19.721 20H21a1 1 0 0 1 0 2h-5a1 1 0 0 1 0-2h1.613L13.051 6.316c-.358-1.073-1.766-1.182-2.701-.967c-.625.145-1.227.449-1.671.917A2.47 2.47 0 0 0 8 8v5a1 1 0 0 1-2 0Z");
}

.t5t8b5byf {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 17a5 5 0 0 1 10 0v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>

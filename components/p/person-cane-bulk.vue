<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rh1kgcbvi"/><path class="ar8ya0f1y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:person-cane-bulk" /></template>
<style>
.ar8ya0f1y {
  d: path("M6.158 3.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558M9 8.434l4.514 2.709a1 1 0 0 1 .343 1.371a1 1 0 0 1-1.371.343L9 10.766v3.029l2.919 6.811a.999.999 0 1 1-1.838.788L8 16.539l-2.081 4.855a.999.999 0 1 1-1.838-.788L7 13.795V8a1 1 0 0 1 2 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.rh1kgcbvi {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.832 20.445a1 1 0 0 1-1.664 1.11l-6-9a1 1 0 0 1 1.664-1.11Z");
}

</style>

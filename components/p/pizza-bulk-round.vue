<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pa6uz-bfa"/><path class="i8n244b0x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pizza-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.i8n244b0x {
  d: path("M12.01 9a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2ZM11 12h.01a1 1 0 0 1 0 2H11a1 1 0 0 1 0-2m4.318 5.117A13.5 13.5 0 0 1 12 17.53a13.5 13.5 0 0 1-6.479-1.652a1 1 0 0 1 .958-1.756a11.52 11.52 0 0 0 11.042 0a1 1 0 0 1 .958 1.756a13.5 13.5 0 0 1-3.161 1.239");
}

.pa6uz-bfa {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m3.106 18.553l8-16a.998.998 0 0 1 1.788 0l8 16a1 1 0 0 1-.423 1.329a17.98 17.98 0 0 1-12.806 1.589a18 18 0 0 1-4.136-1.589a1 1 0 0 1-.423-1.329");
}

</style>

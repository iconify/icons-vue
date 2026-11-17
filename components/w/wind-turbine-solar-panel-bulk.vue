<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i70i6hr0p"/><path class="z5o3n62uu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wind-turbine-solar-panel-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.i70i6hr0p {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.123 7.069a1 1 0 0 1 .401 1.717c-1.219 1.071-2.859.852-4.214.19a2 2 0 0 1-.828-.044l-1.603 1.604a1.002 1.002 0 0 1-1.688-.511c-.318-1.592.692-2.902 1.943-3.745c.1-.26.255-.497.452-.694l-.587-2.191a.999.999 0 0 1 1.286-1.206c.747.253 1.319.77 1.7 1.454c.358.642.521 1.373.572 2.101c.174.216.303.47.375.739Zm-1.115 13.807l1-8A1 1 0 0 1 12 12h8a1 1 0 0 1 .992.876l1 8A.997.997 0 0 1 21 22H11a1 1 0 0 1-.992-1.124");
}

.z5o3n62uu {
  d: path("M8 8.733V21a1 1 0 0 1-2 0V8.733a2.001 2.001 0 1 1 2 0M17 16h3.5a1 1 0 0 1 0 2H17v3a1 1 0 0 1-2 0v-3h-3.5a1 1 0 0 1 0-2H15v-3a1 1 0 0 1 2 0Z");
}

</style>

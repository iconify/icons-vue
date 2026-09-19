<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="voibrgb2b"/><path class="drlt2yhyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-filter-5" /></template>
<style>
.drlt2yhyn {
  fill: currentColor;
  d: path("M19 23v-2H3V5H1v16c0 1.1.9 2 2 2zm-2-10v-2a2 2 0 0 0-2-2h-2V7h4V5h-6v6h4v2h-4v2h4a2 2 0 0 0 2-2m4-12H7c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2m0 16H7V3h14z");
}

.voibrgb2b {
  fill: currentColor;
  d: path("M7 17h14V3H7zm4-4h4v-2h-4V5h6v2h-4v2h2a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vwxsbkybu"/><path class="og8n87e5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-cart-alt-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.og8n87e5k {
  d: path("M3 3h1c.985 0 1.693.83 1.958 1.713L6.344 6H19c.403 0 .792.124 1.122.355c.931.653 1.171 1.927.827 2.961l-1 3C19.664 13.171 18.971 14 18 14H8.744l.21.699a.5.5 0 0 0 .182.129c.266.133.57.172.864.172h8a3 3 0 1 1-2.829 2h-2.342a3.001 3.001 0 1 1-5.218-.815a2.05 2.05 0 0 1-.569-.898l-3-10A.75.75 0 0 0 3.897 5H3a1 1 0 0 1 0-2m5.144 9h9.74a.9.9 0 0 0 .167-.316l1-3c.064-.191.077-.421-.015-.606A.3.3 0 0 0 18.983 8H6.944Zm1.149 5.293a.999.999 0 1 0 1.414 1.414a.999.999 0 1 0-1.414-1.414m8 0a.999.999 0 1 0 1.414 1.414a.999.999 0 1 0-1.414-1.414");
}

.vwxsbkybu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 7c.82 0 1.328 1.016 1 2l-1 3c-.14.419-.495.999-1 1H8L6 7Z");
}

</style>

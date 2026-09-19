<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2ujl0b7j"/><path class="z_zt7pbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-filter-8" /></template>
<style>
.x2ujl0b7j {
  fill: currentColor;
  d: path("M7 17h14V3H7zm4-5.5c0-.83.67-1.5 1.5-1.5c-.83 0-1.5-.67-1.5-1.5V7a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v1.5c0 .83-.67 1.5-1.5 1.5c.83 0 1.5.67 1.5 1.5V13a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2zM13 7h2v2h-2zm0 4h2v2h-2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.z_zt7pbqu {
  fill: currentColor;
  d: path("M21 1H7c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2m0 16H7V3h14zM3 23h16v-2H3V5H1v16c0 1.1.9 2 2 2m10-8h2a2 2 0 0 0 2-2v-1.5c0-.83-.67-1.5-1.5-1.5c.83 0 1.5-.67 1.5-1.5V7a2 2 0 0 0-2-2h-2a2 2 0 0 0-2 2v1.5c0 .83.67 1.5 1.5 1.5c-.83 0-1.5.67-1.5 1.5V13a2 2 0 0 0 2 2m0-8h2v2h-2zm0 4h2v2h-2z");
}

</style>

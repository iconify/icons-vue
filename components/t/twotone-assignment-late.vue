<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sa9fa-3nc"/><path class="vudvy-3xw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-assignment-late" /></template>
<style>
.sa9fa-3nc {
  fill: currentColor;
  d: path("M5 5v14h14V5zm8 12h-2v-2h2zm0-4h-2V7h2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.vudvy-3xw {
  fill: currentColor;
  d: path("M11 15h2v2h-2zm0-8h2v6h-2zm8-4h-4.18C14.4 1.84 13.3 1 12 1s-2.4.84-2.82 2H5c-.14 0-.27.01-.4.04a2.01 2.01 0 0 0-1.44 1.19c-.1.24-.16.49-.16.77v14c0 .27.06.54.16.78s.25.45.43.64c.27.27.62.47 1.01.55c.13.02.26.03.4.03h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m-7-.25c.41 0 .75.34.75.75s-.34.75-.75.75s-.75-.34-.75-.75s.34-.75.75-.75M19 19H5V5h14z");
}

</style>

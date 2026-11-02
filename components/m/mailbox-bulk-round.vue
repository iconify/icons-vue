<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n4lizzbrg"/><path class="zppqoo85k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mailbox-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.n4lizzbrg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 8a5 5 0 0 1 5 5v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5v-4a5 5 0 0 1 5-5Z");
}

.zppqoo85k {
  d: path("M16 9V3a1 1 0 0 1 1-1h4a1 1 0 0 1 0 2h-3v5a1 1 0 0 1-2 0m-4 4v8a1 1 0 0 1-2 0v-8a3 3 0 0 0-3-3a1 1 0 0 1 0-2a4.9 4.9 0 0 1 1.946.393a5 5 0 0 1 1.589 1.072A4.97 4.97 0 0 1 12 13");
}

</style>

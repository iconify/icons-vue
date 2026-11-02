<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="us8y38bnp"/><path class="s4577k2-y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:playing-cards-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.s4577k2-y {
  d: path("M8 2h12a1 1 0 0 1 1 1v14a1 1 0 0 1-2 0V4H8a1 1 0 0 1 0-2m2.832 8.445l2 3a1 1 0 0 1 0 1.11l-2 3a1 1 0 0 1-1.664 0l-2-3a1 1 0 0 1 0-1.11l2-3a1 1 0 0 1 1.664 0M9.202 14L10 15.197L10.798 14L10 12.803Z");
}

.us8y38bnp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 7a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Z");
}

</style>

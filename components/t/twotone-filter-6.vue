<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fckohhbyk"/><path class="swu0_6bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-filter-6" /></template>
<style>
.fckohhbyk {
  fill: currentColor;
  d: path("M7 17h14V3H7zm4-10a2 2 0 0 1 2-2h4v2h-4v2h2a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2zm2 4h2v2h-2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.swu0_6bnk {
  fill: currentColor;
  d: path("M21 1H7c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2m0 16H7V3h14zm-8-2h2a2 2 0 0 0 2-2v-2a2 2 0 0 0-2-2h-2V7h4V5h-4a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2m0-4h2v2h-2zM3 23h16v-2H3V5H1v16c0 1.1.9 2 2 2");
}

</style>

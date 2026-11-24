<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dzd90kxwz"/><path class="sraeltbbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-edit-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dzd90kxwz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m3.106 7.553l1-2C4.848 4.069 6.307 3 8 3h8c1.693 0 3.152 1.069 3.894 2.553l1 2A1 1 0 0 1 20 9H9v11a1 1 0 0 1-1 1a5 5 0 0 1-3.536-1.464A4.98 4.98 0 0 1 3 16V8c0-.155.036-.308.106-.447");
}

.sraeltbbh {
  d: path("M4 7h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2m8 14v-3c0-.265.105-.52.293-.707l5-5a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-5 5A1 1 0 0 1 16 22h-3a1 1 0 0 1-1-1");
}

</style>

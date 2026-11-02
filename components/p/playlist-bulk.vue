<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r5hnoly1a"/><path class="m6cs0kbou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:playlist-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.m6cs0kbou {
  d: path("M21 5a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm-10 6a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm0 6a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

.r5hnoly1a {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m16.447 10.106l4 2a2.116 2.116 0 0 1 0 3.788l-4 2a2.5 2.5 0 0 1-1.119.278c-.427 0-.855-.155-1.112-.508A1.13 1.13 0 0 1 14 17v-6c0-.239.075-.47.216-.664c.257-.353.685-.508 1.112-.508c.39 0 .771.104 1.119.278M16 12.118v3.764l3.553-1.776a.12.12 0 0 0 .065-.106a.12.12 0 0 0-.065-.106Z");
}

</style>

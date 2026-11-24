<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gstn2ybzw"/><path class="yhei9o-nc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-plus-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gstn2ybzw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 17c0-.265.105-.52.293-.707l9-9a2.414 2.414 0 0 1 3.414 0l1 1a2.414 2.414 0 0 1 0 3.414l-9 9A1 1 0 0 1 9 21H6a1 1 0 0 1-1-1Z");
}

.yhei9o-nc {
  d: path("M8 4v2h2a1 1 0 0 1 0 2H8v2a1 1 0 0 1-2 0V8H4a1 1 0 0 1 0-2h2V4a1 1 0 0 1 2 0m6.707 4.293l3 3a.999.999 0 1 1-1.414 1.414l-3-3a.999.999 0 1 1 1.414-1.414");
}

</style>

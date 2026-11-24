<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gapi2ab1b"/><path class="yhei9o-nc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-plus-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gapi2ab1b {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 17c0-.265.105-.52.293-.707l10-10a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-10 10A1 1 0 0 1 9 21H6a1 1 0 0 1-1-1Z");
}

.yhei9o-nc {
  d: path("M8 4v2h2a1 1 0 0 1 0 2H8v2a1 1 0 0 1-2 0V8H4a1 1 0 0 1 0-2h2V4a1 1 0 0 1 2 0m6.707 4.293l3 3a.999.999 0 1 1-1.414 1.414l-3-3a.999.999 0 1 1 1.414-1.414");
}

</style>

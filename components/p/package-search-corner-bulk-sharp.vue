<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ckcfjxbko"/><path class="tky0d4b8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-search-corner-bulk-sharp" /></template>
<style>
.ckcfjxbko {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m3.106 7.553l2-4A1 1 0 0 1 6 3h12c.379 0 .725.214.894.553l2 4A1 1 0 0 1 20 9H9v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V8c0-.155.036-.308.106-.447");
}

.cuyn6tgcc {
  fill: currentColor;
}

.tky0d4b8d {
  d: path("M4 7h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2m15.321 10.907l2.386 2.386a.999.999 0 1 1-1.414 1.414l-2.386-2.386a3.83 3.83 0 1 1 1.414-1.414m-2.028-.614a1.829 1.829 0 1 0-2.587-2.586a1.829 1.829 0 0 0 2.587 2.586");
}

</style>

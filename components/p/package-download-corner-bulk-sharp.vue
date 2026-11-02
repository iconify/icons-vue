<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ckcfjxbko"/><path class="uwjvjlxbb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-download-corner-bulk-sharp" /></template>
<style>
.ckcfjxbko {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m3.106 7.553l2-4A1 1 0 0 1 6 3h12c.379 0 .725.214.894.553l2 4A1 1 0 0 1 20 9H9v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V8c0-.155.036-.308.106-.447");
}

.cuyn6tgcc {
  fill: currentColor;
}

.uwjvjlxbb {
  d: path("M4 7h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2m12.293 14.707l-3-3a1 1 0 0 1 1.414-1.414L16 18.586V13a1 1 0 0 1 2 0v5.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0");
}

</style>

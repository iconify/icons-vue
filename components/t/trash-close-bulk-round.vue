<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a2kniu8dt"/><path class="u2p9fjc0u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trash-close-bulk-round" /></template>
<style>
.a2kniu8dt {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 5h12a1 1 0 0 1 1 1v11a5 5 0 0 1-1.464 3.536A5 5 0 0 1 14 22h-4a5 5 0 0 1-5-5V6a1 1 0 0 1 1-1");
}

.cuyn6tgcc {
  fill: currentColor;
}

.u2p9fjc0u {
  d: path("M11 2h2a3.996 3.996 0 0 1 3.874 3H20a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2h3.126A4 4 0 0 1 11 2m3.733 3A1.99 1.99 0 0 0 13 4h-2a2 2 0 0 0-.276.019h-.001A2.02 2.02 0 0 0 9.267 5Zm-4.026 6.293L12 12.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L13.414 14l1.293 1.293a.999.999 0 1 1-1.414 1.414L12 15.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L10.586 14l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

</style>

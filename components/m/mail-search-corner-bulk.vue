<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zl78s9b-t"/><path class="ecfzikbun"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-search-corner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ecfzikbun {
  d: path("m4.293 4.879l4.414 4.414c.315.315.825.707 1.293.707h4c.468 0 .98-.395 1.293-.707l4.414-4.414a.999.999 0 1 1 1.414 1.414l-4.414 4.414C15.992 11.422 15.039 12 14 12h-4c-1.039 0-1.991-.577-2.707-1.293L2.879 6.293a.999.999 0 1 1 1.414-1.414m15.415 13.414l1.999 2a.999.999 0 1 1-1.414 1.414l-2-1.999a3 3 0 1 1 1.415-1.415m-3.415-.586a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414");
}

.zl78s9b-t {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 12h-8a.997.997 0 0 0-1 1v6a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v4a1 1 0 0 1-1 1");
}

</style>

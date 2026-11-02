<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xsyyzkwrp"/><path class="wtx7gow_f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.wtx7gow_f {
  d: path("M10 18a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm6 3a1 1 0 0 1-2 0V6a1 1 0 0 1 2 0Z");
}

.xsyyzkwrp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.448 2.106L15 4.882l3.553-1.776c.356-.181.75-.274 1.149-.273C20.924 2.836 22 3.735 22 5v12c-.001 1.348-1.478 2.357-2.553 2.894l-4 2a1 1 0 0 1-.894 0L9 19.118l-3.553 1.776c-.356.181-.75.274-1.149.273C3.076 21.164 2 20.265 2 19V7c.001-1.348 1.478-2.357 2.553-2.894l4-2a1 1 0 0 1 .894 0Z");
}

</style>

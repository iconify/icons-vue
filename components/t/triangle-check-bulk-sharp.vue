<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dtro9rbwa"/><path class="x08n7km5w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-check-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dtro9rbwa {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12.874 1.514l10 18A1 1 0 0 1 22 21H2a1 1 0 0 1-.874-1.486l10-18a1 1 0 0 1 1.748 0");
}

.x08n7km5w {
  d: path("M10.892 14.478L13.2 11.4a1 1 0 0 1 1.6 1.2l-3 4a.998.998 0 0 1-1.507.107l-2-2a.999.999 0 1 1 1.414-1.414Z");
}

</style>

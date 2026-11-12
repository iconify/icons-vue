<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o6z2orh3k"/><path class="xcpv1kb9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:markdown-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.o6z2orh3k {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m19 14.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0l-3-3a.999.999 0 1 1 1.414-1.414L17 14.586V7a1 1 0 0 1 2 0Z");
}

.xcpv1kb9w {
  d: path("M2 7a1 1 0 0 1 1.781-.625L7 10.399l3.219-4.024A1.002 1.002 0 0 1 12 7v10a1 1 0 0 1-2 0V9.851l-2.219 2.774a1 1 0 0 1-1.562 0L4 9.851V17a1 1 0 0 1-2 0Z");
}

</style>

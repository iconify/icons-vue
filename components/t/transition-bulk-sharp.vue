<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mnmhpfbqa"/><path class="k52rlhb2l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:transition-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k52rlhb2l {
  d: path("M5 10a7 7 0 0 1 13.989-.403l1.304-1.304a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0l-3-3a.999.999 0 1 1 1.414-1.414l1.275 1.275A5 5 0 0 0 7 10v2a1 1 0 0 1-2 0Z");
}

.mnmhpfbqa {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 18a3 3 0 1 1 6 0a3 3 0 0 1-6 0m12 0a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

</style>

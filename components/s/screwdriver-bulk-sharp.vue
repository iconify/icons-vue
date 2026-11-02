<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kziksqbxa"/><path class="c7vulxbdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:screwdriver-bulk-sharp" /></template>
<style>
.c7vulxbdc {
  d: path("m12.293 10.293l7-7a.999.999 0 1 1 1.414 1.414l-7 7a.999.999 0 1 1-1.414-1.414");
}

.cuyn6tgcc {
  fill: currentColor;
}

.kziksqbxa {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m3.293 15.293l7-7a1 1 0 0 1 1.414 0l4 4a1 1 0 0 1 0 1.414l-7 7a3.828 3.828 0 0 1-5.414-5.414");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xy4m1x57y"/><path class="jwikj1bfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paper-plane-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jwikj1bfu {
  d: path("m10.293 12.293l3-3a.999.999 0 1 1 1.414 1.414l-3 3a.999.999 0 1 1-1.414-1.414");
}

.xy4m1x57y {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.684 2.051a1.001 1.001 0 0 1 1.265 1.265l-6 18a1 1 0 0 1-1.843.131l-3.851-7.702l-7.702-3.851a1 1 0 0 1 .131-1.843Z");
}

</style>

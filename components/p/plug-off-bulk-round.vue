<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cz55xgduo"/><path class="hcv6tgjxe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plug-off-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.cz55xgduo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m15.703 6.297l-9.704 9.704c-.65-.867-1-1.917-.999-3.001v-2a5 5 0 0 1 5-5h4a5 5 0 0 1 1.703.297m1.678 2.565l.722-.722A5 5 0 0 1 19 11v2a5 5 0 0 1-5 5h-4a5 5 0 0 1-1.522-.236Z");
}

.hcv6tgjxe {
  d: path("M1.293 19.293L14 6.586V3a1 1 0 0 1 2 0v1.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-18 18a.999.999 0 1 1-1.414-1.414M10 3v4a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0m3 18a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Z");
}

</style>

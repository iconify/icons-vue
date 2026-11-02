<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="luvn0zfzk"/><path class="n2tzskgxj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-off-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.luvn0zfzk {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.475 15.233L8.243 3H16a5 5 0 0 1 5 5v5a5 5 0 0 1-.525 2.233M4.999 3.999l13.393 13.393c-.734.4-1.556.608-2.392.608H8a5 5 0 0 1-5-5V8c0-1.576.737-3.057 1.999-4.001");
}

.n2tzskgxj {
  d: path("m3.707 1.293l19 19a.999.999 0 1 1-1.414 1.414l-19-19a.999.999 0 1 1 1.414-1.414M9 19h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>

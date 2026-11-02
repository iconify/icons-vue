<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pjl2xdbsb"/><path class="zasdgoimj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zoom-in-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.pjl2xdbsb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 10a8 8 0 1 1 16 0a8 8 0 0 1-16 0");
}

.zasdgoimj {
  d: path("M11 7v2h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2H7a1 1 0 0 1 0-2h2V7a1 1 0 0 1 2 0m10.707 13.293a.999.999 0 1 1-1.414 1.414l-6-6a.999.999 0 1 1 1.414-1.414Z");
}

</style>

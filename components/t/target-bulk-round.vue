<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="riis51qtn"/><path class="ad3vehi6s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:target-bulk-round" /></template>
<style>
.ad3vehi6s {
  d: path("M6.472 9.664a6.001 6.001 0 1 1 11.055 4.674A6.001 6.001 0 0 1 6.472 9.664M16 12a4 4 0 1 0-8 0a4 4 0 0 0 8 0m-4-1h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

.cuyn6tgcc {
  fill: currentColor;
}

.riis51qtn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l3h0twbhh"/><path class="lqgw2rbvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-bag-alt-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.l3h0twbhh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 8a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5Z");
}

.lqgw2rbvs {
  d: path("M15.685 9.557a4 4 0 0 1-4.48 2.363A4 4 0 0 1 8 8a1 1 0 0 1 2 0a2 2 0 1 0 4 0a1 1 0 0 1 2 0a4 4 0 0 1-.315 1.557");
}

</style>

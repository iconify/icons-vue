<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="riis51qtn"/><path class="hbqky-u5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pinterest-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hbqky-u5k {
  d: path("m16.914 9.594l.002.004a5.925 5.925 0 0 1-5.929 8.305l-1.068 2.491a1 1 0 0 1-1.838-.788l1.373-3.205l.001-.002l1.626-3.793a.999.999 0 1 1 1.838.788l-1.078 2.516a3.92 3.92 0 0 0 3.245-2.316l.002-.003a3.926 3.926 0 0 0-4.02-5.492a3.88 3.88 0 0 0-3.154 2.307l-.002.003A3.9 3.9 0 0 0 7.576 12a3.9 3.9 0 0 0 .338 1.594a1.001 1.001 0 0 1-1.828.812A5.9 5.9 0 0 1 5.576 12a5.9 5.9 0 0 1 .51-2.406a5.84 5.84 0 0 1 3.799-3.299a6.06 6.06 0 0 1 3.23 0a5.86 5.86 0 0 1 3.799 3.299");
}

.riis51qtn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12");
}

</style>

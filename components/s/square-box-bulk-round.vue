<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nmk72ab6r"/><path class="w1yznnbgx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-box-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nmk72ab6r {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.5 9.844v4.312c0 .761-.432 1.457-1.114 1.794l-3.5 1.728a2 2 0 0 1-1.772 0l-3.5-1.728A2 2 0 0 1 6.5 14.156V9.844c0-.761.432-1.457 1.114-1.794l3.5-1.728a2 2 0 0 1 1.772 0l3.5 1.728A2 2 0 0 1 17.5 9.844");
}

.w1yznnbgx {
  d: path("M7 2h10a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5M4 17a3 3 0 0 0 3 3h10a3 3 0 0 0 3-3V7a3 3 0 0 0-3-3H7a3 3 0 0 0-3 3Zm8-6.671l3.897-1.924a.999.999 0 1 1 .886 1.793L13 12.066v4.819a1 1 0 0 1-2 0v-4.819l-3.783-1.868a1 1 0 1 1 .886-1.793Z");
}

</style>

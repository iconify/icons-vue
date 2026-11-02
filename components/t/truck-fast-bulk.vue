<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="prgz69brz"/><path class="w9x16qd2t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:truck-fast-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.prgz69brz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 4a3 3 0 0 1 3 3h2c1.039 0 1.992.578 2.707 1.293l2 2C21.422 11.008 22 11.961 22 13v3c0 1.32-.866 2.487-2.128 2.872a3 3 0 0 1-5.701.128H9.829a3 3 0 0 1-5.7-.128A3.005 3.005 0 0 1 2 16V5a1 1 0 0 1 1-1Zm3 8h5.586l-2.707-2.707A1 1 0 0 0 16.172 9H14Zm-7.709 6.705l.002.002l.002.002a1 1 0 0 0 1.41 0l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 0 1.41m11.414.004l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 1.414 1.414");
}

.w9x16qd2t {
  d: path("M3 7h6a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m0 4h4a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m1 7a3 3 0 1 1 6 0a3 3 0 0 1-6 0m10 0a3 3 0 1 1 6 0a3 3 0 0 1-6 0m-8 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m10 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>

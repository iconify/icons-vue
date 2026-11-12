<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yk_q-048u"/><path class="b4p-u2c-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-text-bulk-sharp" /></template>
<style>
.b4p-u2c-w {
  d: path("M3 8h6a1 1 0 0 1 0 2H7v5a1 1 0 0 1-2 0v-5H3a1 1 0 0 1 0-2");
}

.cuyn6tgcc {
  fill: currentColor;
}

.yk_q-048u {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 9h2.586l4.707-4.707A1 1 0 0 1 22 5v14a1.002 1.002 0 0 1-1.707.707L15.586 15H13a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1");
}

</style>

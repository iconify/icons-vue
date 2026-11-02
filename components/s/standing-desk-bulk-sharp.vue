<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m-8y43bnm"/><path class="ftiw0fc3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:standing-desk-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ftiw0fc3q {
  d: path("M4.293 3.293a1 1 0 0 1 1.414 0l2 2a.999.999 0 1 1-1.414 1.414L5 5.414L3.707 6.707a.999.999 0 1 1-1.414-1.414Zm-.586 6L5 10.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-2 2a1 1 0 0 1-1.414 0l-2-2a.999.999 0 1 1 1.414-1.414M17 12v3h4a1 1 0 0 1 1 1v4a1 1 0 0 1-2 0v-3H4v3a1 1 0 0 1-2 0v-4a1 1 0 0 1 1-1h12v-3a1 1 0 0 1 2 0");
}

.m-8y43bnm {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 4a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H11a1 1 0 0 1-1-1Z");
}

</style>

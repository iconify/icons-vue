<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="geiqwsblw"/><path class="d39ywpn1q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rotate-left-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d39ywpn1q {
  d: path("M15.707 3.707L14.414 5H15c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 20 10a1 1 0 0 1-2 0a3 3 0 0 0-3-3h-.586l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414M20 14v2a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 21H9a5 5 0 0 1-5-5V9c0-1.064.418-2.078 1.172-2.828A3.98 3.98 0 0 1 8 5a1 1 0 0 1 0 2a2 2 0 0 0-2 2v7a3 3 0 0 0 3 3h6a3 3 0 0 0 3-3v-2a1 1 0 0 1 2 0");
}

.geiqwsblw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 10a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4v6a4 4 0 0 1-4 4H9a4 4 0 0 1-4-4Z");
}

</style>

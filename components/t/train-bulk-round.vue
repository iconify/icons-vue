<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ub3rkbclc"/><path class="b3lapab3s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:train-bulk-round" /></template>
<style>
.b3lapab3s {
  d: path("M9 13h.01a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m6 0h.01a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2m-6.106 4.447l-2 4a1 1 0 1 1-1.788-.894l2-4a1 1 0 1 1 1.788.894m8-.894l2 4a1 1 0 1 1-1.788.894l-2-4a1 1 0 1 1 1.788-.894");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ub3rkbclc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 18H7a3 3 0 0 1-3-3V8c0-1.317.335-2.748 1.293-3.707l1-1C7.252 2.335 8.683 2 10 2h4c1.317 0 2.748.335 3.707 1.293l1 1C19.665 5.252 20 6.683 20 8v7a3 3 0 0 1-3 3M6 9h12V7.657c0-.794-.315-1.556-.875-2.118l-.004-.003l-.659-.66A3 3 0 0 0 14.343 4H9.657c-.795 0-1.557.315-2.119.876l-.002.003l-.66.659A3 3 0 0 0 6 7.657Z");
}

</style>

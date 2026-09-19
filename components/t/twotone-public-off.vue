<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twb2tfnqu"/><path class="umwyvtbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-public-off" /></template>
<style>
.twb2tfnqu {
  fill: currentColor;
  d: path("m11 8.17l7.88 7.88A7.84 7.84 0 0 0 20 12c0-3.35-2.07-6.22-5-7.41V5c0 1.1-.9 2-2 2h-2zM11 18c-1.1 0-2-.9-2-2v-1l-4.79-4.79C4.08 10.79 4 11.38 4 12c0 4.08 3.05 7.44 7 7.93z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.umwyvtbsr {
  fill: currentColor;
  d: path("M11 8.17L6.49 3.66A9.9 9.9 0 0 1 12 2c5.52 0 10 4.48 10 10c0 2.04-.61 3.93-1.66 5.51l-1.46-1.46A7.84 7.84 0 0 0 20 12c0-3.35-2.07-6.22-5-7.41V5c0 1.1-.9 2-2 2h-2zm10.19 13.02l-1.41 1.41l-2.27-2.27A9.84 9.84 0 0 1 12 22C6.48 22 2 17.52 2 12c0-2.04.61-3.93 1.66-5.51L1.39 4.22L2.8 2.81zM11 18c-1.1 0-2-.9-2-2v-1l-4.79-4.79C4.08 10.79 4 11.38 4 12c0 4.08 3.05 7.44 7 7.93z");
}

</style>

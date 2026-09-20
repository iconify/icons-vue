<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ceneugbao"/><path class="x1m35dd6x"/><path class="jjnbvub1x"/><path class="h1c4l9bix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xdata" /></template>
<style>
.ceneugbao {
  fill: var(--svg-color--f0c419, #f0c419);
  d: path("M12 9.828c4.17 0 7.549-1.528 7.549-3.414C19.549 4.53 16.169 3 12 3S4.452 4.529 4.452 6.414S7.832 9.828 12 9.828");
}

.ft5dv1b6b {
  fill: none;
}

.h1c4l9bix {
  fill: var(--svg-color--7a69a7, #7a69a7);
  d: path("M4.452 15.414v2.172C4.452 19.473 7.832 21 12 21c4.17 0 7.549-1.527 7.549-3.414v-2.172h-.03c-.348 1.742-3.582 3.1-7.519 3.1s-7.17-1.358-7.52-3.1z");
}

.jjnbvub1x {
  fill: var(--svg-color--e64c3c, #e64c3c);
  d: path("M4.452 11.692v2.172c0 1.881 3.38 3.414 7.548 3.414c4.17 0 7.549-1.533 7.549-3.414v-2.172h-.03c-.348 1.742-3.582 3.101-7.519 3.101s-7.17-1.364-7.52-3.1z");
}

.x1m35dd6x {
  fill: var(--svg-color--25ae5f, #25ae5f);
  d: path("M4.452 7.964v2.172c0 1.887 3.38 3.414 7.548 3.414c4.17 0 7.549-1.527 7.549-3.414V7.97h-.03c-.348 1.736-3.582 3.1-7.519 3.1S4.83 9.707 4.48 7.965z");
}

</style>

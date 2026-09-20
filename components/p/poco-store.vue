<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2wj9jbhp"/><path class="vu590obhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:poco-store" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.vu590obhd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.743 28v-8h2.619a2.684 2.684 0 0 1 2.681 2.687c0 1.484-1.2 2.686-2.681 2.686H9.743m20.776-.056v.033a2.65 2.65 0 1 1-5.3 0v-2.7a2.65 2.65 0 1 1 5.3 0v.033M20.131 20za2.644 2.644 0 0 1 2.65 2.65v2.7a2.644 2.644 0 0 1-2.65 2.65a2.644 2.644 0 0 1-2.65-2.65v-2.7a2.644 2.644 0 0 1 2.65-2.65m15.476 0za2.644 2.644 0 0 1 2.65 2.65v2.7a2.644 2.644 0 0 1-2.65 2.65a2.644 2.644 0 0 1-2.65-2.65v-2.7a2.644 2.644 0 0 1 2.65-2.65");
}

</style>

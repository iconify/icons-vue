<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4ugu5o_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-sale" /></template>
<style>
.e4ugu5o_h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.52 22.076q-.317-.264-1.031-.845Q2.75 14.929 2.75 11q.001-3.831 2.71-6.539T12 1.753t6.54 2.708T21.25 11q0 3.929-7.739 10.231q-.714.581-1.031.845q-.05.042-.107.074q-.056.033-.118.055t-.125.034q-.065.011-.13.011t-.13-.011q-.064-.012-.125-.034q-.062-.022-.118-.055q-.057-.032-.107-.074M9.849 6.585q-2.076.188-2.264 2.264l-.147 1.62q-.106 1.166.722 1.994l3.133 3.133q.732.733 1.767.733q1.036 0 1.768-.733l1.768-1.768q.733-.732.733-1.767q0-1.036-.733-1.768L13.463 7.16q-.828-.828-1.994-.722z");
}

</style>

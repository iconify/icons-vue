<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5_f2jbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:search-insights-rounded" /></template>
<style>
.s5_f2jbtg {
  fill: currentColor;
  d: path("M10 16.039q2.5 0 4.25-1.756T16 10.019t-1.75-4.264T10 4T5.75 5.756T4 10.019t1.75 4.264T10 16.039m-.357-3.587q-.143-.143-.143-.356V7.135q0-.213.144-.357t.357-.143t.356.143t.143.357v4.961q0 .213-.144.357t-.357.143t-.356-.143m-3.346 0q-.143-.144-.143-.357V9.04q0-.213.144-.357t.357-.143t.356.143t.143.357v3.057q0 .213-.144.357q-.144.143-.357.143t-.356-.143m6.693 0q-.144-.144-.144-.357V10q0-.213.144-.356q.144-.144.357-.144t.356.144t.143.356v2.096q0 .213-.144.356t-.356.144t-.356-.144M10 17q-2.931 0-4.966-2.033Q3 12.933 3 10.003t2.034-4.966T9.997 3t4.967 2.034Q17 7.07 17 10q0 1.317-.457 2.493t-1.256 2.086l5.379 5.379q.14.134.14.34t-.14.358t-.354.14t-.354-.15l-5.36-5.36q-.929.8-2.105 1.257T10 17");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zv2ij86ob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mark-email-read-outline-sharp" /></template>
<style>
.zv2ij86ob {
  fill: currentColor;
  d: path("m15.489 21.27l-3.558-3.558l.708-.708l2.85 2.85l5.688-5.688l.708.707zM12 11l7.692-5H4.308zm0 1.116L4 6.885v10.5q0 .269.173.442t.443.173H9.4l1 1H3V5h18v6.542l-1 1V6.885zm0 0");
}

</style>

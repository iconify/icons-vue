<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryflyfqvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:markdown-rate" /></template>
<style>
.ryflyfqvm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 12q-.001 4.039 2.855 6.896T12 21.753t6.895-2.857T21.75 12q.001-4.039-2.855-6.896T12 2.247q-4.04 0-6.895 2.857Q2.249 7.961 2.25 12m7-5q.828 0 1.414.586T11.25 9t-.586 1.414T9.25 11q-2 0-2-2t2-2m.319 8.988q-.097.113-.23.181t-.281.079t-.291-.035q-.142-.046-.255-.144q-.056-.048-.102-.106t-.079-.124t-.053-.137t-.026-.144q-.005-.074.003-.147q.009-.074.032-.144t.059-.135t.085-.12l6-7q.048-.056.106-.102t.124-.079t.137-.053t.144-.026t.147.003t.144.032t.135.059t.12.085t.102.106q.045.058.079.124q.033.066.053.137t.026.144t-.003.147t-.032.144t-.059.135t-.085.12zM12.75 15q0-2 2-2t2 2t-2 2t-2-2");
}

</style>

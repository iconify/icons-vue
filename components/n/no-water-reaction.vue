<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us5xzwb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:no-water-reaction" /></template>
<style>
.us5xzwb7c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.057 16.229L8.549 5.72q.976-1.373 2.203-2.873q.465-.569.662-.816q.052-.065.117-.117q.117-.093.26-.134t.292-.025q.148.016.279.088q.13.072.224.188q.197.247.662.816Q19.25 10.182 19.25 14.5q0 .904-.193 1.729M4.03 2.97l17 17q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-17-17q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 3.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094M12 21.75q2.886 0 4.96-1.962L6.37 9.199Q4.75 12.257 4.75 14.5q0 3.003 2.123 5.127T12 21.75");
}

</style>

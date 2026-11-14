<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3nt4xllf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:message-disappearing" /></template>
<style>
.c3nt4xllf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.25 4.5v1.25q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T8 6.5t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V4.5q0-1.25 1.25-1.25h9.5q1.25 0 1.25 1.25V11q0 1.25-1.25 1.25h-.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T18 13t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.75q2.75 0 2.75-2.75V4.5q0-2.75-2.75-2.75H10q-2.75 0-2.75 2.75M2.555 8.555q-.805.806-.805 1.945V16q0 2.75 2.75 2.75h.25V21q0 .134.047.26q.046.126.134.228q.048.056.106.102t.124.079t.137.053t.144.026q.074.005.147-.003q.074-.009.144-.032t.135-.059t.12-.085l3.289-2.819H14q2.75 0 2.75-2.75v-5.5q0-2.75-2.75-2.75H4.5q-1.139 0-1.945.805");
}

</style>

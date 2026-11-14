<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-j-6ibdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:queue-position" /></template>
<style>
.e-j-6ibdf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.5 2.75h-9Q8.25 2.75 8.25 5t2.25 2.25h9q2.25 0 2.25-2.25T19.5 2.75M6.03 11.47l-2.5-2.5q-.052-.053-.113-.094t-.13-.069t-.141-.043T3 8.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.106.105-.163.243T2.25 9.5t.057.287t.163.243L4.439 12L2.47 13.97q-.106.105-.163.243t-.057.287t.057.287t.163.243q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l2.5-2.5q.106-.105.163-.243T6.25 12t-.057-.287t-.163-.243m4.47-1.72h9q2.25 0 2.25 2.25t-2.25 2.25h-9q-2.25 0-2.25-2.25t2.25-2.25m9 7h-9q-2.25 0-2.25 2.25t2.25 2.25h9q2.25 0 2.25-2.25t-2.25-2.25");
}

</style>

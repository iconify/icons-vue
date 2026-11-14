<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1z-t4qbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:rocket-launch" /></template>
<style>
.h1z-t4qbd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.47 5.47l-2.781 2.78H7q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T6.25 9q0 .149.057.287t.163.243l2 2l4 4l2 2q.105.106.243.163t.287.057q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-3.689l2.78-2.781q.044-.044.08-.094q2.763-3.868 1.561-6.271q-.055-.109-.141-.195t-.195-.141q-2.403-1.202-6.271 1.561q-.05.036-.094.08M9 9.939l-.189-.189h.378zm5.25 5.25L14.061 15l.189-.189zM4.5 21.75q-2.25 0-2.25-2.25q0-1.87 1.554-2.186q.307-1.826 2.361-2.237q2.188-.437 2.891 1.221q1.694.316 1.694 2.702q0 2.75-2.25 2.75z");
}

</style>

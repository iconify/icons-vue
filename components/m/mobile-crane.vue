<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="am_qcwbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mobile-crane" /></template>
<style>
.am_qcwbdl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.75 10V5q0-.139-.05-.269q-.05-.129-.143-.233l-.027-.028q-.105-.106-.243-.163T18 4.25q-.139 0-.269.05q-.129.05-.233.143L7.712 13.25H5.25q-1.036 0-1.768.732T2.75 15.75v.5q0 1.036.732 1.768q.307.307.668.485q-.4.549-.4 1.497q0 2.25 2.25 2.25T8.25 20q0-.75-.25-1.25h4q-.25.5-.25 1.25q0 2.25 2.25 2.25q.932 0 1.591-.659T16.25 20q0-.704-.376-1.253q.956-.041 1.644-.729q.732-.732.732-1.768v-.5q0-2.5-2.5-2.5H9.954l7.296-6.566V10q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146");
}

</style>

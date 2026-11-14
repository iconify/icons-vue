<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxnh5w3qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:search" /></template>
<style>
.mxnh5w3qa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.02 5.02Q2.75 7.29 2.75 10.5t2.27 5.48t5.48 2.27q2.829 0 4.927-1.762l4.543 4.542q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-4.542-4.543q1.762-2.098 1.762-4.927q0-3.21-2.27-5.48T10.5 2.75T5.02 5.02m1.061 9.899Q4.25 13.089 4.25 10.5t1.831-4.419T10.5 4.25t4.419 1.831q1.831 1.83 1.831 4.419t-1.831 4.419T10.5 16.75t-4.419-1.831");
}

</style>

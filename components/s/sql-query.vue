<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7sbzp3sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sql-query" /></template>
<style>
.m7sbzp3sp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 5.499Q2.752 2.25 10 2.25q7.25 0 7.25 3.25v7.756q-.806.042-1.5.357v-.329q-1.798.966-5.75.966t-5.75-.966V16q0 1.75 5.75 1.75q1.959 0 3.25-.203q.008.773.257 1.446q-1.466.257-3.507.257q-7.25 0-7.25-3.25zm13 5.501V7.784q-1.798.966-5.75.966t-5.75-.966V11q0 1.75 5.75 1.75T15.75 11m1.75 3.5q-3 0-3 3t3 3q.97 0 1.626-.313l1.344 1.343q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-1.343-1.344q.313-.656.313-1.626q0-3-3-3m0 4.5Q16 19 16 17.5t1.5-1.5t1.5 1.5t-1.5 1.5");
}

</style>

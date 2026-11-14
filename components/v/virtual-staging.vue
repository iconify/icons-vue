<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z16te9bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:virtual-staging" /></template>
<style>
.z16te9bak {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.125 2.25h13.75q1.398 0 2.386.989q.989.988.989 2.386v12.75q0 3.375-3.375 3.375H5.125q-3.375 0-3.375-3.375V5.625q0-1.398.989-2.386q.988-.989 2.386-.989M7.25 12.257q-2 .122-2 2.243v3q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h12q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-3q0-2.121-2-2.243V10.5q0-2.25-2.25-2.25h-5q-2.25 0-2.25 2.25zm1.5.243q.914.457.993 1.75h4.514q.079-1.293.993-1.75v-2q0-.75-.75-.75h-5q-.75 0-.75.75z");
}

</style>

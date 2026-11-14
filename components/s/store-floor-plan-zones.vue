<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bx3docfzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:store-floor-plan-zones" /></template>
<style>
.bx3docfzv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 21.75H4q-2.25 0-2.25-2.25v-15q0-2.25 2.25-2.25h16q2.25 0 2.25 2.25v15q0 2.25-2.25 2.25h-6q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T13.25 21t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h6q.75 0 .75-.75V9.75h-10.5V13q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H3.25v5.75q0 .75.75.75h6q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014m-1.25-18v8.5h-5.5V4.5q0-.75.75-.75zm4.911 0H10.25v4.5h1.161zm1.678 0l-2.25 4.5h2.072l2.25-4.5zm3.322 4.5l1.918-3.835q.054-.108.139-.193q-.123-.472-.718-.472h-.911l-2.25 4.5zm1.678 0h.411v-.823z");
}

</style>

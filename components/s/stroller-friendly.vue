<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqzh8pbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:stroller-friendly" /></template>
<style>
.lqzh8pbou {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.227 5.227Q3.25 7.204 3.25 10t1.977 4.773T10 16.75t4.773-1.977q1.919-1.919 1.975-4.61l1.739-3.913H20.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014H18q-.109 0-.213.031t-.196.09t-.162.142t-.114.182L15.513 9.25H10.75V4q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q10.074 3.25 10 3.25q-2.796 0-4.773 1.977M9.25 9.25H4.798q.224-1.697 1.49-2.962q1.265-1.266 2.962-1.49zM6.5 16.5Q4 16.5 4 19t2.5 2.5T9 19t-2.5-2.5M11 19q0-2.5 2.5-2.5T16 19t-2.5 2.5T11 19");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxaavxujm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:school-bag" /></template>
<style>
.wxaavxujm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.359 5.641q-.927-.927-2.11-1.236Q15.202 2.25 13 2.25h-2q-2.202 0-2.249 2.155q-1.183.309-2.11 1.236Q5.25 7.032 5.25 9v10q0 2.75 2.75 2.75h8q2.75 0 2.75-2.75V9q0-1.968-1.391-3.359M15.5 21.75q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T14.75 21v-4.5q0-.75-.75-.75h-4q-.75 0-.75.75V21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T7.75 21v-4.5q0-2.25 2.25-2.25h4q.932 0 1.591.659t.659 1.591V21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014m-1.775-17.5h-3.45q.113-.5.725-.5h2q.612 0 .725.5");
}

</style>

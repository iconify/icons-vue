<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="saahphbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:race-control" /></template>
<style>
.saahphbzn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.928 2.25h12.144q1.28 0 2.028 1.038t.344 2.252l-.833 2.5q-.57 1.71-2.372 1.71H14.75v10.5H17q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T6.25 21q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T7 20.25h2.25V9.75H6.761q-1.802 0-2.372-1.71l-.833-2.5q-.404-1.214.344-2.252T5.928 2.25m7.322 7.5v10.5h-2.5V9.75z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf-2jzd_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tile" /></template>
<style>
.rf-2jzd_s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.75 2.25h-7.5q-2.485 0-4.243 1.757Q2.25 5.765 2.25 8.25v7.5q0 2.485 1.757 4.243Q5.765 21.75 8.25 21.75h7.5q2.485 0 4.243-1.757q1.757-1.758 1.757-4.243v-7.5q0-2.485-1.757-4.243Q18.235 2.25 15.75 2.25m-9 7.25q0-2.75 2.75-2.75H13q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T13 8.25H9.5q-1.25 0-1.25 1.25V13q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T6.75 13z");
}

</style>

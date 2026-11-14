<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-j5bwk9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:webcam" /></template>
<style>
.i-j5bwk9w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.52 4.52Q4.25 6.79 4.25 10t2.27 5.48q2 2 4.73 2.238v2.032H8q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h8q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T16 19.75h-3.25v-2.032q2.73-.238 4.73-2.238q2.27-2.27 2.27-5.48t-2.27-5.48T12 2.25T6.52 4.52M12 6.75q3.25 0 3.25 3.25T12 13.25T8.75 10T12 6.75m0 5q-1.75 0-1.75-1.75T12 8.25T13.75 10T12 11.75");
}

</style>

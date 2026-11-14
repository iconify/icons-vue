<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wnq9ncbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:user-clock" /></template>
<style>
.wnq9ncbol {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 8.25q0-1.864 1.318-3.182T9 3.75t3.182 1.318T13.5 8.25t-1.318 3.182T9 12.75t-3.182-1.318T4.5 8.25m10 2.75q0-4 4-4t4 4t-4 4t-4-4m1.5 0q0 2.5 2.5 2.5T21 11t-2.5-2.5T16 11m3.25-.311V9.75q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T18.5 9t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146V11q0 .149.057.287t.163.243l1 1q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.106-.105.163-.243T20.25 12t-.057-.287t-.163-.243zM3.963 15.985Q1.75 17.573 1.75 20q0 1.75 1.75 1.75h11q1.75 0 1.75-1.75q0-2.427-2.213-4.015Q11.97 14.5 9 14.5t-5.037 1.485");
}

</style>

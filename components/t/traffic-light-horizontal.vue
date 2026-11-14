<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t53qz6y8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:traffic-light-horizontal" /></template>
<style>
.t53qz6y8l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15 2.25H9q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T8.25 3t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043q.072.014.146.014h2.25v3H6.5q-2.175 0-3.712 1.538Q1.25 9.825 1.25 12t1.538 3.712Q4.325 17.25 6.5 17.25h11q2.175 0 3.712-1.538Q22.75 14.175 22.75 12t-1.538-3.712Q19.675 6.75 17.5 6.75h-4.75v-3H15q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T15.75 3t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q15.074 2.25 15 2.25M4 12q0-2.5 2.5-2.5T9 12t-2.5 2.5T4 12m8-2.5q1.036 0 1.768.732T14.5 12t-.732 1.768T12 14.5q-2.5 0-2.5-2.5T12 9.5m3 2.5q0-2.5 2.5-2.5T20 12t-2.5 2.5T15 12");
}

</style>

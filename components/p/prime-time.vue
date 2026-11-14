<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jp8ebc5tv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:prime-time" /></template>
<style>
.jp8ebc5tv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 2.75H6q-1.76 0-3.005 1.245T1.75 7v7.5q0 1.76 1.245 3.005T6 18.75h12q1.76 0 3.005-1.245T22.25 14.5V7q0-1.76-1.245-3.005T18 2.75M8.288 7.038Q9.825 5.5 12 5.5t3.712 1.538q1.538 1.537 1.538 3.712t-1.538 3.712Q14.175 16 12 16t-3.712-1.538Q6.75 12.925 6.75 10.75t1.538-3.712M15.5 20.25q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T7.75 21q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>

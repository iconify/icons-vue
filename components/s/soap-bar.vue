<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj-h05iel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:soap-bar" /></template>
<style>
.hj-h05iel {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 4q0-2.25 2.25-2.25T14.5 4t-2.25 2.25T10 4m-3 .5q-2.75 0-2.75 2.75T7 10t2.75-2.75T7 4.5m9.75 0q-3.25 0-3.25 3.25T16.75 11T20 7.75T16.75 4.5M7.5 11.75h9q2.175 0 3.712 1.538Q21.75 14.825 21.75 17t-1.538 3.712Q18.675 22.25 16.5 22.25h-9q-2.175 0-3.712-1.538Q2.25 19.175 2.25 17t1.538-3.712Q5.325 11.75 7.5 11.75m3.5 3.5H7q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T6.25 16t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h4q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T11 15.25");
}

</style>

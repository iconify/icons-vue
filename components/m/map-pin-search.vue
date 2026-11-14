<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7j6egb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:map-pin-search" /></template>
<style>
.p7j6egb4v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.509 22.067Q3.75 15.342 3.75 9.5q0-3.417 2.416-5.834T12 1.25t5.834 2.416Q20.25 6.083 20.25 9.5q0 5.842-7.759 12.567q-.051.044-.108.078q-.058.034-.121.058q-.063.023-.129.035T12 22.25t-.133-.012t-.129-.035q-.063-.024-.121-.058t-.108-.078M14.5 9q0-3-3-3t-3 3t3 3q.97 0 1.626-.313l1.094 1.093q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113l-1.093-1.094Q14.5 9.97 14.5 9");
}

</style>

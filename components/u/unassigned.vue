<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k12-2wbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:unassigned" /></template>
<style>
.k12-2wbxp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.641 4.141Q7.25 5.532 7.25 7.5t1.391 3.359T12 12.25t3.359-1.391T16.75 7.5t-1.391-3.359T12 2.75T8.641 4.141M3.75 21q0-2.971 2.441-4.901Q8.53 14.25 12 14.25t5.809 1.849Q20.25 18.029 20.25 21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-15q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T3.75 21");
}

</style>

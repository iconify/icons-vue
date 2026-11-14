<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pshpfeigv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sludge" /></template>
<style>
.pshpfeigv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.5 5q0-2 2-2t2 2t-2 2t-2-2m7 1Q15 6 15 8.5t2.5 2.5T20 8.5T17.5 6M1.75 20.5q0-4.943 2.419-7.911Q6.482 9.75 10 9.75q2.021 0 4.185 1.733q.957.767 1.315.767q6.75 0 6.75 8.25q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1snaroij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:plinth-pedestal" /></template>
<style>
.g1snaroij {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 7.25q0-2.278 1.611-3.889T12 1.75t3.889 1.611T17.5 7.25t-1.611 3.889q-.056.057-.114.111H18.5q2.25 0 2.25 2.25q0 1.837-1.5 2.174V21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-13q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-5.826q-1.5-.337-1.5-2.174q0-.932.659-1.591T5.5 11.25h2.725q-.058-.054-.114-.111Q6.5 9.528 6.5 7.25m11.25 13.5v-5H6.25v5z");
}

</style>

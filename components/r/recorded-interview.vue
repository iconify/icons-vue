<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2dxeq-_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:recorded-interview" /></template>
<style>
.w2dxeq-_t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 9.5q0-3.21 2.27-5.48t5.48-2.27t5.48 2.27t2.27 5.48t-2.27 5.48q-2 2-4.73 2.238v.553q4.5.257 4.5 3.729q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-2.25-3.75-2.25T6.75 21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T6 22.25t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-3.472 4.5-3.729v-.553q-2.73-.238-4.73-2.238q-2.27-2.27-2.27-5.48m15-5.5q0-1.75 1.75-1.75T21.25 4T19.5 5.75T17.75 4M10.5 5.75q-3.75 0-3.75 3.75t3.75 3.75t3.75-3.75t-3.75-3.75");
}

</style>

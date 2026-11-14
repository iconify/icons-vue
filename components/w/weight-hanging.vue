<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8uajbekq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:weight-hanging" /></template>
<style>
.j8uajbekq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 1.75H6q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043q.072.014.146.014h5.25v2.054Q9 5.652 9 8.25q0 .979.319 1.639q-1.02.343-1.437 1.535l-2.275 6.5q-.427 1.219.321 2.273q.747 1.053 2.039 1.053h8.066q1.292 0 2.039-1.053q.748-1.054.321-2.273l-2.275-6.5q-.417-1.192-1.437-1.535Q15 9.229 15 8.25q0-2.598-2.25-2.946V3.25H18q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T18 1.75");
}

</style>

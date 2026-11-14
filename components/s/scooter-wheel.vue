<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bs_hnsb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:scooter-wheel" /></template>
<style>
.bs_hnsb1c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 10.794q-1.903.228-3.316 1.64Q6.25 14.118 6.25 16.5t1.684 4.066T12 22.25t4.066-1.684T17.75 16.5t-1.684-4.066q-1.413-1.412-3.316-1.64V4.25H16q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T16 2.75H8q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043T8 4.25h3.25z");
}

</style>

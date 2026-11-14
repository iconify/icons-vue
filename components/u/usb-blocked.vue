<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsdptz7xk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:usb-blocked" /></template>
<style>
.hsdptz7xk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 1.75h-3.5q-2.5 0-2.5 2.5v3q0 .913.569 1.591q-.437.266-.824.654Q3.75 10.74 3.75 12.5V18q0 1.76 1.245 3.005T8 22.25h3q1.76 0 3.005-1.245q.298-.297.524-.624Q15.455 22 18 22q4 0 4-4t-4-4q-1.764 0-2.75.778V12.5q0-1.76-1.245-3.005q-.387-.388-.824-.654q.569-.678.569-1.591v-3q0-2.5-2.5-2.5M10.75 5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T7.5 5.75t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T8.25 5z");
}

</style>

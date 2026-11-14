<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0hsn876l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:policy-print" /></template>
<style>
.r0hsn876l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.75 8.926q.978.292 1.755 1.069Q20.75 11.24 20.75 13v1q0 1.76-1.245 3.005q-.777.777-1.755 1.069V20.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-2.426q-.978-.292-1.755-1.069Q3.25 15.76 3.25 14v-1q0-1.76 1.245-3.005q.777-.777 1.755-1.069V3.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q6.926 2.75 7 2.75h10q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146zm-10-.176h8.5v-4.5h-8.5z");
}

</style>

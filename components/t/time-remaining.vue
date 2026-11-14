<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5xogvbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:time-remaining" /></template>
<style>
.e5xogvbyb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752m7.998 6.498h5.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 3.003-2.123 5.127T12 19.25t-5.127-2.123Q4.75 15.003 4.75 12t2.123-5.127Q8.997 4.75 12 4.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146zm-1.5-4.956V12q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h5.706q-.228 1.903-1.64 3.316Q14.382 17.75 12 17.75t-4.066-1.684T6.25 12t1.684-4.066q1.413-1.412 3.316-1.64");
}

</style>

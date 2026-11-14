<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gp8mvy8xz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:unrestricted-fund" /></template>
<style>
.gp8mvy8xz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 1.5q-3.25 0-3.25 3.25T8 8q1.346 0 2.298-.952t.952-2.298t-.952-2.298T8 1.5m7.5.5q3 0 3 3t-3 3t-3-3t3-3m1 7.25h-10q-1.76 0-3.005 1.245T2.25 13.5v4q0 1.76 1.245 3.005T6.5 21.75h10q1.76 0 3.005-1.245T20.75 17.5v-4q0-1.76-1.245-3.005T16.5 9.25m4.25 4.25q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-3.25q-1 0-1 1t1 1H20q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-3.25q-2.5 0-2.5-2.5t2.5-2.5H20q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>

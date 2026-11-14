<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e47dk7bou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:org-welcome-sign" /></template>
<style>
.e47dk7bou {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 2.75H6q-1.76 0-3.005 1.245T1.75 7v4q0 1.76 1.245 3.005q1.155 1.156 2.755 1.239V21.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-6.25h9.5v6.25q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-6.256q1.6-.083 2.755-1.239Q22.25 12.76 22.25 11V7q0-1.76-1.245-3.005T18 2.75m-6.416 10.124Q8 10.485 8 8.25q0-3 3-3q.569 0 1 .318q.431-.318 1-.318q3 0 3 3q0 2.235-3.584 4.624q-.092.062-.199.094Q12.111 13 12 13t-.217-.032t-.199-.094");
}

</style>

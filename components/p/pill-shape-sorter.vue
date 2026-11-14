<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4rzm2bxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pill-shape-sorter" /></template>
<style>
.e4rzm2bxy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 3.75H6.875q-2.123 0-3.624 1.501T1.75 8.875v6.25q0 2.123 1.501 3.624t3.624 1.501h10.25q2.123 0 3.624-1.501t1.501-3.624v-6.25q0-2.123-1.501-3.624T17.125 3.75zm0 0q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v15q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-15q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m4.75 3q2.75 0 2.75 2.75v5q0 2.75-2.75 2.75T14 14.5v-5q0-2.75 2.75-2.75M10.25 12q0 3-3 3t-3-3t3-3t3 3");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9a6-pbte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:rep-commission" /></template>
<style>
.a9a6-pbte {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752M8.75 6.25q2.5 0 2.5 2.5t-2.5 2.5t-2.5-2.5t2.5-2.5m6.72 1.22q.052-.053.113-.094t.13-.069t.141-.043T16 7.25t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243T16.75 8t-.057.287t-.163.243l-8 8q-.105.106-.243.163T8 16.75t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141T7.25 16q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113zm-2.72 7.78q0-2.5 2.5-2.5t2.5 2.5t-2.5 2.5t-2.5-2.5");
}

</style>

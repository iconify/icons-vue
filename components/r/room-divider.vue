<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nom_plb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:room-divider" /></template>
<style>
.nom_plb-g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 6.5V21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T3.75 21v-1.75h16.5V21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V6.5q0-3.75-3.75-3.75q-2.073 0-3 1.146q-.927-1.146-3-1.146T9 3.896Q8.073 2.75 6 2.75q-3.75 0-3.75 3.75m13.5 11.25V6.5q0-2.25 2.25-2.25t2.25 2.25v11.25zM14.25 6.5v11.25h-4.5V6.5q0-2.25 2.25-2.25t2.25 2.25m-6 11.25h-4.5V6.5q0-2.25 2.25-2.25T8.25 6.5z");
}

</style>

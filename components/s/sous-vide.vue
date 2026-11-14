<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggme9ebah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sous-vide" /></template>
<style>
.ggme9ebah {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.5 1.75q2.75 0 2.75 2.75v2.25H20q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v11q0 2.75-2.75 2.75H6q-2.75 0-2.75-2.75V10q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T4 9.25t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v1.943q.775-.053 1.779.348q1.232.494 1.785.099q1.22-.872 3.214-.074q.795.318 1.222.231V4.5q0-2.75 2.75-2.75m-2.75 12.307q-.775.053-1.779-.348q-1.232-.494-1.785-.099q-1.22.872-3.214.074q-.795-.318-1.222-.231V18.5q0 1.25 1.25 1.25h12q1.25 0 1.25-1.25V8.25h-1v7.25q0 2.75-2.75 2.75t-2.75-2.75z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dn8gdq4bm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:safety-car" /></template>
<style>
.dn8gdq4bm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.75 2.25h3q1.75 0 1.75 1.75t-1.75 1.75h-3Q9 5.75 9 4t1.75-1.75m-9 10.5v2.5q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043T2.5 16h1.753q-.503.771-.503 1.75q0 1.346.952 2.299q.951.952 2.298.952t2.298-.952q.952-.953.952-2.299q0-.979-.503-1.75h4.337q-.334.708-.334 1.75Q13.75 21 17 21t3.25-3.25q0-1.042-.334-1.75H21.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2.5q0-2.201-2.153-2.249l-1.714-.428L15.53 7.22q-.105-.106-.243-.163T15 7H9.5q-.167 0-.318.071t-.258.199l-2.322 2.786l-2.667.444q-2.185.033-2.185 2.25");
}

</style>

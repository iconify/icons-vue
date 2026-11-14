<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytw_lfbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:roof-felt" /></template>
<style>
.ytw_lfbve {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 1.75Q3.25 1.75 3.25 5v14q0 1.499 1.879 2.439q1.623.811 3.871.811q5.75 0 5.75-3.25V7.276q5 .362 5 5.724v8.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V13q0-6.865-6.5-7.23V5q0-3.25-5.75-3.25M4.75 19V7.232q.179.106.379.207Q6.752 8.25 9 8.25q2.813 0 4.25-.778V19q0 1.75-4.25 1.75T4.75 19");
}

</style>

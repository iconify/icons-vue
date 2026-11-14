<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zuytbxbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:start-lights-out" /></template>
<style>
.zuytbxbzz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.085 8.585q-.585.586-.585 1.414v.002q0 .828.585 1.414q.586.586 1.415.586t1.415-.586t.585-1.416q.001-.827-.585-1.414q-.586-.586-1.415-.586t-1.415.586M1.5 10q0 .829.586 1.414Q2.671 12 3.5 12t1.414-.586Q5.5 10.828 5.5 10t-.586-1.414Q4.329 8 3.5 8t-1.414.586Q1.5 9.171 1.5 10m4.25 0q0-2 2-2t2 2t-2 2t-2-2M12 8q-2 0-2 2t2 2t2-2t-2-2m2.25 2q0-2 2-2t2 2t-2 2t-2-2m7.25 3.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141q-.014-.072-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>

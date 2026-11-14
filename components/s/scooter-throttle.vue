<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phzm2gb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:scooter-throttle" /></template>
<style>
.phzm2gb9i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.659 8.813L9.382 5.691q-.358-.875.102-1.7q.461-.825 1.393-.981l.237-.039q1.894-.315 2.502 1.508l1.161 3.48q.136.41.084.791H19q1.346 0 2.298.952T22.25 12q0 3.25-3.25 3.25h-7.5q-2.85 0-3.201-2.5H5.75v8.75q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T5 22.25t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-8.75H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 12.074 1.75 12t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h5.799q.295-2.104 2.36-2.437");
}

</style>

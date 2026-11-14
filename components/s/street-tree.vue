<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwk5i6bnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:street-tree" /></template>
<style>
.fwk5i6bnv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.984 12.214q.453 2.939 3.369 3.521q.073.015.147.015h3.75v4.5H7q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T6.25 21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h10q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T17 20.25h-4.25v-1.939l2.561-2.561H16.5q.074 0 .147-.015q2.916-.582 3.369-3.521q.428-2.785-1.89-4.217q-1.464-4.32-6.126-4.32t-6.126 4.32q-2.318 1.432-1.89 4.217m9.205 3.536l-.439.439v-.439z");
}

</style>

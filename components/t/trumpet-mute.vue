<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xb6t2_y8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:trumpet-mute" /></template>
<style>
.xb6t2_y8m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.233 2.25h1.534q1.761 0 2.354 1.659l3.75 10.5q.419 1.171-.252 2.195q1.131.633 1.131 2.396q0 2.75-2.75 2.75H7q-2.75 0-2.75-2.75q0-1.763 1.131-2.396q-.671-1.024-.252-2.195l3.75-10.5q.593-1.659 2.354-1.659m4.267 5h-7q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T7.75 8t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h7q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T16.25 8t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>

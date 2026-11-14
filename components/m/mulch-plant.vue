<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hco9nkb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mulch-plant" /></template>
<style>
.hco9nkb0z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.223 16.512q-2.321-.683-5.473-.754v-5.025q7-.318 7-6.733q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T19 3.25q-4.34 0-6.25 2.117V4q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q12.074 3.25 12 3.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T11.25 4v5.459Q9.452 7.75 5.5 7.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 5.444 6.5 5.734v1.524q-3.152.071-5.473.754q-3.027.891-3.027 2.487v.002q0 1.596 3.027 2.487q2.593.763 6.223.763t6.223-.763q3.029-.891 3.027-2.489q.002-1.596-3.027-2.487");
}

</style>

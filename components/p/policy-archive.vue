<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fq0grui1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:policy-archive" /></template>
<style>
.fq0grui1f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 3.25h13q1.346 0 2.298.952T21.75 6.5t-.952 2.298q-.259.26-.548.448V18q0 2.75-2.75 2.75h-11q-2.75 0-2.75-2.75V9.416q-1.5-.708-1.5-2.916q0-1.346.952-2.298T5.5 3.25m-.25 6.495V18q0 1.25 1.25 1.25h11q1.25 0 1.25-1.25V9.742q-.123.008-.25.008h-13q-.128 0-.25-.005M14 12.25h-4q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T9.25 13t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h4q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T14 12.25");
}

</style>

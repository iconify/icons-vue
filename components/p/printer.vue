<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r27j8bbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:printer" /></template>
<style>
.r27j8bbdl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.5 7.25h-1.25V4.5q0-1.75-1.75-1.75h-9q-1.75 0-1.75 1.75v2.75H4.5q-1.139 0-1.945.805Q1.75 8.861 1.75 10v5q0 2.75 2.75 2.75h1.25v1q0 2.5 2.5 2.5h7.5q2.5 0 2.5-2.5v-1h1.25q2.75 0 2.75-2.75v-5q0-2.75-2.75-2.75M7.25 4.5v2.75h9.5V4.5q0-.25-.25-.25h-9q-.25 0-.25.25m10.76 5.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141q.014.072.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H18q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T17.25 11t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>

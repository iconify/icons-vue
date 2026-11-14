<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rw5sxuyrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:room-scan" /></template>
<style>
.rw5sxuyrg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 2.25h15q2.25 0 2.25 2.25v15q0 2.25-2.25 2.25H14q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-5.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T14 14.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146V21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H4.5q-2.25 0-2.25-2.25v-15q0-.493.184-.909l-.126-.301q-.057-.138-.058-.287t.056-.287t.161-.244t.243-.164T3 2.25t.29.058l.301.126q.416-.184.909-.184");
}

</style>

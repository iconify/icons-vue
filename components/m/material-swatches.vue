<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="huhkkyjms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:material-swatches" /></template>
<style>
.huhkkyjms {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 15.25h4.25V18q0 1.76 1.245 3.005T13 22.25h5q1.76 0 3.005-1.245T22.25 18v-5q0-1.76-1.245-3.005T18 8.75h-2.75V4.5q0-2.75-2.75-2.75h-8q-1.139 0-1.945.805q-.805.806-.805 1.945v8q0 2.75 2.75 2.75m17.75 2.25q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-12q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h12q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146m-19-11.75V4.5q0-.518.366-.884T4.5 3.25h8q1.25 0 1.25 1.25v1.25zm10.5 3H13q-1.76 0-3.005 1.245T8.75 13v.75H4.5q-1.25 0-1.25-1.25V7.25h10.5z");
}

</style>

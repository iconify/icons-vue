<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z599zabuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:media-player-file" /></template>
<style>
.z599zabuq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2.75h12q1.76 0 3.005 1.245T22.25 7v10q0 1.76-1.245 3.005T18 21.25H6q-1.76 0-3.005-1.245T1.75 17V7q0-1.76 1.245-3.005T6 2.75m7.414 5.352l-1.206-.768h-.001q-1.123-.714-2.29-.073T8.75 9.233v1.534q0 1.331 1.167 1.972t2.291-.073l1.206-.768q1.041-.664 1.041-1.898t-1.041-1.898M18 15.75H6q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h12q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T18 15.75");
}

</style>

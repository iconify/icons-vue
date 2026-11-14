<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="derm5bbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:trailer-parking" /></template>
<style>
.derm5bbec {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17 3.75H7q-1.76 0-3.005 1.245T2.75 8v8q0 1.76 1.245 3.005T7 20.25h10q1.76 0 3.005-1.245T21.25 16V8q0-1.76-1.245-3.005T17 3.75M8.25 13V8q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T9 7.25h3.5q3.25 0 3.25 3.25q0 1.346-.952 2.298t-2.298.952H9.75v2.75q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T9 17.25t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146zm1.5-.75h2.75q.725 0 1.237-.513q.513-.512.513-1.237q0-1.75-1.75-1.75H9.75z");
}

</style>

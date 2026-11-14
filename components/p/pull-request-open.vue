<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbuks4bcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pull-request-open" /></template>
<style>
.nbuks4bcm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2Q3 2 3 5q0 2.598 2.25 2.946v8.108Q3 16.402 3 19q0 3 3 3t3-3q0-2.598-2.25-2.946V7.946Q9 7.598 9 5q0-3-3-3m12 0q3 0 3 3q0 2.598-2.25 2.946V11q0 1.968-1.391 3.359T14 15.75h-2.689l.969.97q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.105.106-.243.163T11.75 18t-.287-.057t-.243-.163l-2.25-2.249v-.001q-.106-.105-.163-.243T8.75 15t.057-.287t.163-.243l2.25-2.25q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113l-.969.97H14q3.25 0 3.25-3.25V7.946Q15 7.598 15 5q0-3 3-3");
}

</style>

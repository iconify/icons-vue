<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obbpp_rvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:telescopic-rod" /></template>
<style>
.obbpp_rvx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.244 10.817q.822 1.299-.477 2.597l-2.474 2.475q-.542.543-1.27.639q.027.205.027.422q0 1.243-.879 2.121l-1.768 1.768q-.878.879-2.121.879t-2.121-.879q-.879-.878-.879-2.121t.879-2.121l1.768-1.768q.878-.879 2.121-.879q.217 0 .422.027q.096-.728.639-1.27l2.475-2.474q1.299-1.299 2.597-.477l2.176-2.175l-.353-.354q-.106-.105-.163-.243t-.057-.287t.057-.287t.163-.243t.243-.163t.287-.057q.149 0 .287.057t.243.163l.353.353l3.36-3.359q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.106.105.163.243t.057.287t-.057.287t-.163.243L17.48 7.58l.353.354q.106.105.163.243t.057.287t-.057.287t-.163.243q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094l-.354-.353z");
}

</style>

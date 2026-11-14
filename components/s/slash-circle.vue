<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_d-qlb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:slash-circle" /></template>
<style>
.v_d-qlb4w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.367 16.572L3.97 18.97q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.105.106.243.163t.287.057t.287-.057t.243-.163l2.398-2.397Q9.379 19.25 12 19.25q3.003 0 5.127-2.123T19.25 12q0-2.621-1.617-4.572L20.03 5.03q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094l-2.398 2.397Q14.621 4.75 12 4.75q-3.003 0-5.127 2.123T4.75 12q0 2.621 1.617 4.572");
}

</style>

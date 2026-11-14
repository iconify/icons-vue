<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8t4xc5nt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sunlight-window" /></template>
<style>
.g8t4xc5nt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 1.75h12q1.76 0 3.005 1.245T22.25 6v12q0 1.76-1.245 3.005T18 22.25H6q-1.76 0-3.005-1.245T1.75 18V6q0-1.76 1.245-3.005T6 1.75M16.75 4.5Q14 4.5 14 7.25T16.75 10t2.75-2.75t-2.75-2.75M5.78 19.28l4-4q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T9.25 14t-.146.014q-.073.015-.141.043t-.13.069t-.113.094l-4 4q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.105.106.243.163t.287.057t.287-.057t.243-.163");
}

</style>

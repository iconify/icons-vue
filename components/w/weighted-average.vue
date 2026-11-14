<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uo0qp_bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:weighted-average" /></template>
<style>
.uo0qp_bfj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.5 7.75h-2q-2.25 0-2.25 2.25v2q0 2.25 2.25 2.25H2q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h20q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T22 14.25h-2.5q2 0 2-2t-2-2t-2 2t2 2h-10q2.25 0 2.25-2.25v-2q0-2.25-2.25-2.25m4.402 9.607l.279.441q.71 1.124.068 2.288t-1.97 1.164h-.558q-1.329 0-1.97-1.164q-.642-1.164.068-2.287l.279-.442q.662-1.048 1.902-1.048t1.902 1.048");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1rb4sb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:twofa-hardware-key" /></template>
<style>
.j1rb4sb7a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.5 7.75h-4q-1.76 0-3.005 1.245T2.25 12t1.245 3.005T6.5 16.25h4q1.76 0 3.005-1.245q.971-.971 1.185-2.255h2.56V15q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2.25H21q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 11.25h-6.31q-.214-1.284-1.185-2.255Q12.26 7.75 10.5 7.75M4.75 12q0-2.25 2.25-2.25T9.25 12T7 14.25T4.75 12");
}

</style>

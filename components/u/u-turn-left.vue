<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbdasfbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:u-turn-left" /></template>
<style>
.zbdasfbzn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.75 10v10q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V10q0-2.382-1.684-4.066T12.5 4.25T8.434 5.934T6.75 10v4.189L5.03 12.47q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.106.105-.163.243T3.75 13t.057.287t.163.243l3 3q.105.106.243.163t.287.057q.148 0 .285-.056t.242-.16l.003-.004l3-3q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094l-1.72 1.719V10q0-1.76 1.245-3.005T12.5 5.75t3.005 1.245T16.75 10");
}

</style>

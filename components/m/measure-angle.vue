<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkd9b-v8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:measure-angle" /></template>
<style>
.vkd9b-v8j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.469 12.471L2.47 18.47q-.106.105-.163.243T2.25 19t.057.287t.163.243t.243.163t.287.057h18q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 18.25h-8.778q-.223-2.977-2.179-5.232L17.53 5.53q.106-.105.163-.243T17.75 5t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043T17 4.25q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094zm.509 1.611q1.526 1.81 1.738 4.168H4.811z");
}

</style>

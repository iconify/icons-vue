<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4dus8axi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:power-strip" /></template>
<style>
.p4dus8axi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 3.75h12q1.76 0 3.005 1.245T22.25 8v1q0 1.76-1.245 3.005T18 13.25h-5.25v2.25q0 1.581 2.182 2.559q2.818 1.264 2.818 3.441q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-1.206-1.932-2.072q-3.068-1.376-3.068-3.928v-2.25H6q-1.76 0-3.005-1.245T1.75 9V8q0-1.76 1.245-3.005T6 3.75M4.75 8.5q0 2.25 2.25 2.25T9.25 8.5T7 6.25T4.75 8.5M12 6.25q-2.25 0-2.25 2.25T12 10.75t2.25-2.25T12 6.25m2.75 2.25q0 2.25 2.25 2.25t2.25-2.25T17 6.25T14.75 8.5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1vw0pbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:moisture-meter" /></template>
<style>
.w1vw0pbvq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 1.75h4q1.76 0 3.005 1.245T18.25 6v5.5q0 1.76-1.245 3.005q-.777.777-1.755 1.069V21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-5.75h-3.5v5.75q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-5.926q-.978-.292-1.755-1.069Q5.75 13.26 5.75 11.5V6q0-1.76 1.245-3.005T10 1.75m3.25 2.5h-2.5q-2.5 0-2.5 2.5v2.5q0 2.5 2.5 2.5h2.5q1.036 0 1.768-.732t.732-1.768v-2.5q0-1.036-.732-1.768T13.25 4.25");
}

</style>

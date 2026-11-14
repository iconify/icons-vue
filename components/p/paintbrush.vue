<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ia9ymhbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:paintbrush" /></template>
<style>
.ia9ymhbtb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.811 10.25l.158.159q.66.659.66 1.591t-.66 1.591l-.378.378q-.376.377-.841.538q0 .043-.006.086q-.403 3.227-3.858 5.3Q6.791 21.75 3 21.75q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.25 21q0-3.791 1.857-6.886q2.073-3.455 5.3-3.858q.043-.006.086-.006q.161-.465.538-.841l.378-.378q.659-.66 1.591-.66t1.591.66l.159.158l6.22-6.219q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243t.057.287t-.057.287t-.163.243z");
}

</style>

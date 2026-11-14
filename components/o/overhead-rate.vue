<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtk_o2b1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:overhead-rate" /></template>
<style>
.dtk_o2b1n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 6q0-3 3-3t3 3t-3 3t-3-3m.47 8.97l11.5-11.5q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.106.105.163.243T16.25 4t-.057.287t-.163.243l-11.5 11.5q-.105.106-.243.163T4 16.25t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141q-.014-.072-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113M16.5 13.5q0-3-3-3t-3 3t3 3q.608 0 1.093-.123q.134-.153.291-.297h.001l1.447-1.327q.168-.542.168-1.253m-.771 3.501l1.5-1.375q1.521-1.395 3.042 0l1.5 1.375q.729.669.729 1.659v1.59q0 2.25-2.25 2.25h-3Q15 22.5 15 20.25v-1.59q0-.99.729-1.659m2.514-.269l-1.5 1.375q-.243.223-.243.553v1.59q0 .75.75.75h3q.75 0 .75-.75v-1.59q0-.33-.243-.553l-1.5-1.375q-.507-.465-1.014 0");
}

</style>

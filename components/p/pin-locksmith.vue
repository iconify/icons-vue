<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvov9hdif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-locksmith" /></template>
<style>
.dvov9hdif {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.75 8.5q-.001-2.382 1.683-4.067T15.5 2.748t4.067 1.685T21.25 8.5q.001 2.382-1.683 4.067T15.5 14.252q-1.999 0-3.506-1.185L9.311 15.75l.969.97q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.105.106-.243.163T9.75 18t-.287-.057t-.243-.163l-.97-.969l-1.439 1.439l1.469 1.47q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.105.106-.243.163T7.75 21t-.287-.057t-.243-.163l-1.47-1.469l-1.72 1.719q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113l2.249-2.25h.001v-.001l2.5-2.499l3.214-3.214Q9.749 10.498 9.75 8.5m3.5 0q0 2.25 2.25 2.25t2.25-2.25t-2.25-2.25t-2.25 2.25");
}

</style>

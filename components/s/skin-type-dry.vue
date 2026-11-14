<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxz54ebtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:skin-type-dry" /></template>
<style>
.bxz54ebtv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 14.5q0 1.129.281 2.141L15.527 5.645q-1.149-1.527-2.611-3.23l-.347-.403q-.048-.056-.106-.102t-.124-.079t-.137-.053t-.144-.026q-.074-.005-.147.003q-.074.009-.144.032t-.135.059t-.12.085q-.044.037-.081.081l-.347.403Q4.25 10.374 4.25 14.5M21.03 4.03l-17 17q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113l17-17q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243t.057.287t-.057.287t-.163.243M6.686 20.142L17.811 9.017q1.939 3.286 1.939 5.483q0 3.21-2.27 5.48T12 22.25q-3.093 0-5.314-2.108");
}

</style>

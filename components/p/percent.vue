<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dz7l_xl7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:percent" /></template>
<style>
.dz7l_xl7b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 7q0 1.346.952 2.299q.951.952 2.298.952t2.298-.952q.952-.953.952-2.299t-.952-2.299T7 3.749t-2.298.952Q3.75 5.654 3.75 7m1.22 10.97l13-13q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243t.057.287t-.057.287t-.163.243l-13 13q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113m8.78-.97q0-3.25 3.25-3.25T20.25 17T17 20.25T13.75 17");
}

</style>

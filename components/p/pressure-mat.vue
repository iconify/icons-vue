<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpd475a0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pressure-mat" /></template>
<style>
.fpd475a0m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m12.53 12.03l3.499-3.5q.106-.105.163-.243T16.25 8t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094l-2.22 2.219V3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q12.074 2.25 12 2.25t-.146.014t-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T11.25 3v6.689L9.03 7.47q-.105-.106-.243-.163T8.5 7.25t-.287.057t-.243.163t-.163.243T7.75 8t.057.287t.163.243l3.499 3.5h.001q.104.105.241.162t.285.058H12q.149 0 .287-.057t.243-.163m4.009 2.22q1.372-.001 2.11 1.157l1.272 2.001q.794 1.247.083 2.545t-2.192 1.297H6.188q-1.48 0-2.192-1.297q-.711-1.298.083-2.546l1.272-1.999q.738-1.159 2.11-1.158z");
}

</style>

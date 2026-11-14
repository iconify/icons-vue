<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e31nyyslw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:note-check" /></template>
<style>
.e31nyyslw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.25 6q0-2.75 2.75-2.75h12q2.75 0 2.75 2.75v8q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 13.25h-4q-2.75 0-2.75 2.75v4q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H6q-2.75 0-2.75-2.75zM10 11.939L8.53 10.47q-.052-.053-.113-.094t-.13-.069t-.141-.043T8 10.25t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.106.105-.163.243T7.25 11t.057.287t.163.243l2 2q.105.106.243.163t.287.057t.287-.057t.243-.163l4-4q.053-.052.094-.113t.069-.13t.043-.141T14.75 9t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.105-.106-.243-.163T14 8.25t-.287.057t-.243.163zm10 2.811q.149 0 .287-.057t.243-.163l-6 6q.106-.105.163-.243T14.75 20v-4q0-1.25 1.25-1.25z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p987mbdap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:psychiatrist" /></template>
<style>
.p987mbdap {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15 1.75h5q2.25 0 2.25 2.25v6q0 2.25-2.25 2.25h-2.189l-2.281 2.28q-.105.106-.243.163T15 14.75t-.287-.057t-.243-.163t-.163-.243q-.057-.138-.057-.287v-1.826q-1.5-.337-1.5-2.174V4q0-2.25 2.25-2.25M3.5 9.5q0-4 4-4q1.657 0 2.828 1.172Q11.5 7.843 11.5 9.5t-1.172 2.828Q9.157 13.5 7.5 13.5q-4 0-4-4m4 5.25q-5.75 0-5.75 6.25q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T3.25 21q0-4.75 4.25-4.75T11.75 21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-6.25-5.75-6.25");
}

</style>

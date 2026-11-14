<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dp1j9rbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:possession-stat" /></template>
<style>
.dp1j9rbpk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752m6.498 7.009V2.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146V12q0 .239-.138.434l-5.5 7.75q-.087.122-.213.201t-.273.104q-.148.025-.293-.008t-.267-.119q-.06-.043-.111-.097q-.051-.053-.09-.116t-.066-.132q-.026-.069-.038-.141q-.013-.073-.011-.147t.019-.146q.016-.072.046-.139q.031-.068.073-.128z");
}

</style>

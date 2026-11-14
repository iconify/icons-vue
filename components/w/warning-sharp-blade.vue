<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyn-zun5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:warning-sharp-blade" /></template>
<style>
.pyn-zun5n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.985 6.549Q14.036 4.748 12 4.748T9.015 6.549L3.869 16.3q-.89 1.686.095 3.318q.984 1.632 2.89 1.632h10.292q1.906 0 2.89-1.632t.095-3.318zM9.75 18v-7.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q.236 0 .43.136Q14.5 12.385 14.5 18q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H10.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T9.75 18");
}

</style>

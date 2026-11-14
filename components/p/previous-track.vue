<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynm5-zriz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:previous-track" /></template>
<style>
.ynm5-zriz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 18V6q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T3.5 5.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q2.75 5.926 2.75 6v12q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T4.25 18M17.623 7.907q1.216-1.043 2.672-.374q1.455.67 1.455 2.272v4.39q0 1.602-1.455 2.272t-2.672-.374l-2.561-2.194q-.642-.55-.812-1.317v1.613q0 1.602-1.455 2.272t-2.672-.374l-2.561-2.194Q6.689 13.15 6.689 12t.873-1.898l2.561-2.195q1.216-1.043 2.672-.374q1.455.67 1.455 2.272v1.613q.17-.767.812-1.316z");
}

</style>

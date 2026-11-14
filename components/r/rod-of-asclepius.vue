<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2n31ng4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:rod-of-asclepius" /></template>
<style>
.e2n31ng4b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 4.897V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q12.074 1.75 12 1.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v7.397Q7.5 10.805 7.5 13t3.75 3.103V21.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-.896q3.75-.891 3.75-2.854t-3.75-2.854v-3.793Q16.5 10.195 16.5 8t-3.75-3.103m0 1.545Q15 7.04 15 8t-2.25 1.558zm-1.5 5v3.116Q9 13.96 9 13t2.25-1.558m1.5 4.994Q15 17.002 15 17.75t-2.25 1.314z");
}

</style>

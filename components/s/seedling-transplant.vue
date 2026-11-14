<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9axg_tla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:seedling-transplant" /></template>
<style>
.o9axg_tla {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 5.5q0 4.879 4.75 5.224v3.526h-5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146q0 2.493 1.801 4.173Q5.24 20.75 7.5 20.75q2.943 0 5.007-1.521q1.908-1.406 2.193-3.479h1.388Q16.419 17 18 17h2.25q2 0 2-2t-2-2H18q-1.581 0-1.912 1.25H9V9.721Q13.75 9.344 13.75 4q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q13.074 3.25 13 3.25q-4.034 0-5.109 3.093Q6.53 4.75 3.5 4.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146");
}

</style>

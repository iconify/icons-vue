<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxfhc6bok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tor" /></template>
<style>
.sxfhc6bok {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 3.75h2q2.75 0 2.75 2.75q0 1.08-.424 1.736q.924.67.924 2.264q0 .959-.334 1.583q1.334.666 1.334 2.667q0 1.217-.494 1.94q1.834.84 4.274 3.28q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-3.281-3.28-4.97-3.28H8q-1.689 0-4.97 3.28q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q2.44-2.44 4.274-3.28q-.494-.723-.494-1.94q0-2.294 1.753-2.834q-.253-.581-.253-1.416q0-2.459 2.199-2.719Q9.25 7.24 9.25 6.5q0-2.75 2.75-2.75");
}

</style>

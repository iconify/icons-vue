<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v27cn3b9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:rounders-bat" /></template>
<style>
.v27cn3b9c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.54 11.439q-.937 1.177-.306 2.266l-3.951 3.952l-.354-.353q-.105-.106-.243-.163t-.287-.057t-.287.057t-.243.163q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113l.86.861l.023.023l.023.023l.861.86q.105.106.243.163t.287.057t.287-.057t.243-.163q.053-.052.094-.113t.069-.13t.043-.141q.014-.072.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-.353-.353l3.952-3.952q1.089.631 2.266-.306l6.151-4.895q.876-.698.939-1.815q.063-1.118-.729-1.909l-.762-.763q-.792-.792-1.91-.729t-1.815.939zM14 17.5q0-3.5 3.5-3.5t3.5 3.5t-3.5 3.5t-3.5-3.5");
}

</style>

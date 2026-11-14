<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_mlzcc3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:milk-carton" /></template>
<style>
.m_mlzcc3r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m15.614 3.57l3.5 4.999q-.052-.074-.12-.133t-.148-.101t-.168-.064t-.178-.021H9.75V4q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q9.074 3.25 9 3.25h6q.09 0 .178.021t.168.064q.081.042.149.101t.119.134m-7.229 0q-.135.194-.135.43v4.25H5.5q-.09 0-.178.021t-.168.064q-.08.041-.148.101q-.068.059-.12.133zM9 9.75H5.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T4.75 9v10q0 2.75 2.75 2.75h9q2.75 0 2.75-2.75V9q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014z");
}

</style>

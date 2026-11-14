<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jik2_3bpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:speedway-bike" /></template>
<style>
.jik2_3bpy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.09 8.357q-1.34.901-1.34 3.143q0 3.75 3.75 3.75t3.75-3.75t-3.75-3.75q-.537 0-.998.077l-.831-1.662v-.001l-1.5-2.999q-.047-.094-.117-.171t-.16-.132t-.189-.083q-.101-.029-.205-.029H12q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h2.036l.75 1.5H9q-.09 0-.178.021t-.168.064q-.081.042-.149.101t-.119.134L7.063 7.959Q6.386 7.75 5.5 7.75q-3.75 0-3.75 3.75t3.75 3.75t3.75-3.75q0-1.833-.896-2.77L9.39 7.25h6.146zM1.75 18.75Q1.75 16 12 16t10.25 2.75T12 21.5q-4.013 0-6.872-.602q-3.378-.711-3.378-2.148");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqws7cb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:race-track" /></template>
<style>
.gqws7cb1v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.093 10.462q-2.685-1.555-6.343-1.698v-1.59q.337.076.75.076H16q2.25 0 2.25-2.25V4q0-2.25-2.25-2.25h-2.5q-.599 0-1.038.159q-.099-.077-.218-.118q-.118-.041-.244-.041q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v6.264q-3.658.143-6.343 1.698Q1.75 12.289 1.75 15t3.157 4.538Q7.864 21.25 12 21.25t7.093-1.712Q22.25 17.711 22.25 15t-3.157-4.538M6.25 15q0-2.5 5.75-2.5t5.75 2.5T12 17.5T6.25 15");
}

</style>

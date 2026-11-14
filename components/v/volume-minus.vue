<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kifefbbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:volume-minus" /></template>
<style>
.kifefbbmf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.828 8.25H5.25q-2.5 0-2.5 2.5v2.5q0 1.036.732 1.768t1.768.732h1.578q.384 0 .669.256l2.001 1.802q1.085.976 2.418.382q1.333-.593 1.334-2.053V7.863q-.001-1.46-1.334-2.053q-1.333-.594-2.418.383l-2.001 1.8q-.285.257-.669.257m14.672 3h-6q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h6q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>

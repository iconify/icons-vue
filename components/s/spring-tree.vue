<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcppfupug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:spring-tree" /></template>
<style>
.pcppfupug {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 4.25q0-3 2-3t2 3q0 2.372-1.25 2.868v3.071l4.22-4.219q.039-.039.083-.072Q17 5.489 17 5q0-3 2-3t2 3t-2 3q-.874 0-1.366-.573l-4.884 4.884V21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-6.189l-4.884-4.884Q5.874 11 5 11q-2 0-2-3t2-3t2 3q0 .489-.053.898q.044.033.083.072l4.22 4.219V7.118Q10 6.622 10 4.25");
}

</style>

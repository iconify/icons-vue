<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zoi5g5b8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:marker-circle" /></template>
<style>
.zoi5g5b8x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 9.75q0-3.417 2.416-5.834T12 1.5t5.834 2.416Q20.25 6.333 20.25 9.75t-2.416 5.834q-2.147 2.146-5.084 2.386v3.53q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-3.53q-2.937-.24-5.084-2.386Q3.75 13.167 3.75 9.75m5 0Q8.75 6.5 12 6.5t3.25 3.25T12 13T8.75 9.75");
}

</style>

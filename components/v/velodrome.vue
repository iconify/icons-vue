<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdnppfbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:velodrome" /></template>
<style>
.zdnppfbpa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 5.75h4q2.589 0 4.419 1.831Q22.25 9.411 22.25 12t-1.831 4.419T16 18.25H8q-2.589 0-4.419-1.831Q1.75 14.589 1.75 12t1.831-4.419Q5.411 5.75 8 5.75zm.75 3.75v-3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T12 5.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v3H8.5Q6 9.5 6 12q0 1.036.732 1.768T8.5 14.5h7q1.036 0 1.768-.732T18 12q0-2.5-2.5-2.5z");
}

</style>

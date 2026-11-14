<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgj1ibb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:swab-test" /></template>
<style>
.cgj1ibb0r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.858 9.03q1.944-1.944 0-3.888t-3.888 0L12.142 7.97q-1.658 1.658-.488 3.316L4.47 18.47q-.053.052-.094.113t-.069.13t-.043.141T4.25 19q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.105.106.243.163T5 19.75t.287-.057t.243-.163l7.184-7.184q1.658 1.17 3.316-.488z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7w531boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:plant-label" /></template>
<style>
.p7w531boz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.625 2.25h4.788q1.398 0 2.386.989l6.875 6.875q2.386 2.386 0 4.772l-4.788 4.788q-2.386 2.386-4.772 0l-6.875-6.875q-.989-.988-.989-2.386V5.625q0-1.398.989-2.386q.988-.989 2.386-.989M7.75 5.5Q5.5 5.5 5.5 7.75T7.75 10T10 7.75T7.75 5.5M10 14.75q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014q4.75 0 4.75-4.75q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T14.75 10Q10 10 10 14.75");
}

</style>

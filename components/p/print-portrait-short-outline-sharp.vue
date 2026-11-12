<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcz37ccyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:print-portrait-short-outline-sharp" /></template>
<style>
.mcz37ccyb {
  fill: currentColor;
  d: path("M6.925 5H17zm-2.7 10h9.5q1.375-2.3 2.238-4.812T17 5H6.925Q6.8 7.625 6.05 10.113T4.225 15M2.45 17l-.775-1.225Q3.05 12.725 3.9 9.537T4.925 3h2.05V2h3v1H14V2h3v1h1l1 1q-.225 3.475-1.3 6.75T14.85 17zm2.525 4v-5h2v3H17V4h2v17z");
}

</style>

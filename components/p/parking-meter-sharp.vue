<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aw75xoyil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:parking-meter-sharp" /></template>
<style>
.aw75xoyil {
  fill: currentColor;
  d: path("M9.058 20v-2H3v-6.846h5.873L7.4 7H3V6h5.127l2.161 6.154V20zm-2.192-4.308q.47 0 .793-.322q.322-.322.322-.793t-.322-.793q-.322-.323-.793-.323t-.794.323t-.322.793t.322.793t.794.322m8.23-8.634H16q.116-.339.389-.544T17 6.308t.612.206t.388.544h.904q-.154-.7-.679-1.167T17 5.423t-1.225.468t-.679 1.167M15 9.788h4v-.884h-4zM16.5 20v-7.423h-2.52l-1.107-4.258q-.056-.273-.096-.54t-.04-.521q0-1.72 1.226-2.989T17 3t3.038 1.27t1.226 2.988q0 .254-.041.52q-.04.268-.096.541l-1.108 4.258H17.5V20z");
}

</style>

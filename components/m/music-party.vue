<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x59llpb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:music-party" /></template>
<style>
.x59llpb9a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.116 11.774v24.452M8.804 16.833v14.334M4.5 21.471v5.058m12.957-9.696v14.334m4.49-9.696v5.058m12.722-14.755v24.452m-4.312-19.393v14.334m-4.304-9.696v5.058m12.957-9.696v14.334m4.49-9.696v5.058");
}

</style>

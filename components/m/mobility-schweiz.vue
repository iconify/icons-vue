<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="egx4-vbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mobility-schweiz" /></template>
<style>
.egx4-vbtt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.764 21.362a8.12 8.12 0 0 1 8.118-8.119h0A8.12 8.12 0 0 1 24 21.362v13.395M7.764 13.243v21.514M24 21.362a8.12 8.12 0 0 1 8.118-8.119h0a8.12 8.12 0 0 1 8.118 8.119v13.395m-35.736 0h6.527M4.5 13.451l3.264-.208m12.972 21.514h6.528m9.709 0H43.5");
}

</style>

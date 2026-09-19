<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u16_n90iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:read-city" /></template>
<style>
.u16_n90iw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.625 34.5l-3.5-21H40l3.5 21zM22.5 13.5l-1.75 21H4.5v-21zm7.625 21v-21H27l-1.75 21zm7 0v-21h-5v21z");
}

</style>

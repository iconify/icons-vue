<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="live53bgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:osmdashboardforopentracks" /></template>
<style>
.live53bgs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.69 11.34L13.28 26L24 27l3.9 9.74Zm-30.2 4.5L32.01 5.5m.83 15.1l9.67 5.41m-25.92-14.5l10.15 5.67m-.14 16.26l-7.88 9.06m17.44-20.04l-6.02 6.92");
}

</style>

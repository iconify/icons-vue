<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lj3ynjvaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:truecoach" /></template>
<style>
.lj3ynjvaj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.915 13.688L24 4.5l16.085 9.188m-5.873 7.686L24 16.264l-11.915 6.813v13.618L24 43.5l10.212-5.11h0");
}

</style>

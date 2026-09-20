<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtgih872k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:metro" /></template>
<style>
.wtgih872k {
  fill: currentColor;
  d: path("M4 20V4h2.954L12 17.339L17.015 4H20v16h-1.846V6.366L12.89 20h-1.8L5.846 6.46V20z");
}

</style>

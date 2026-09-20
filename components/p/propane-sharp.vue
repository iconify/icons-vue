<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7xqj1bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:propane-sharp" /></template>
<style>
.x7xqj1bfw {
  fill: currentColor;
  d: path("M9.5 7h5V5.808h-5zM7 19v-2q-2.077 0-3.538-1.457T2 12.005T3.458 8.46T7 7h1.5V4.808h7V7H17q2.083 0 3.542 1.457T22 11.995t-1.458 3.544Q19.083 17 17 17v2h-1v-2H8v2z");
}

</style>

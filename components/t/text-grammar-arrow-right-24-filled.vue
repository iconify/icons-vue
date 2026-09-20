<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt6f6t3eg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-grammar-arrow-right-24-filled" /></template>
<style>
.rt6f6t3eg {
  fill: currentColor;
  d: path("M3 5h18a1 1 0 0 1 .117 1.993L21 7H3a1 1 0 0 1-.117-1.993zm0 6a1 1 0 0 1-.117-1.993L3 9h18a1 1 0 0 1 .117 1.993L21 11zm0 4h8.498a6.5 6.5 0 0 1 1.312-2H3l-.117.007A1 1 0 0 0 3 15m0 2h8.019a6.6 6.6 0 0 0 .155 2H3a1 1 0 0 1-.117-1.993zm9 .5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 0 0-11 0m6.35 2.854l-.07.057a.5.5 0 0 1-.637-.057l-.058-.07a.5.5 0 0 1 .058-.638L19.289 18H14.5l-.09-.008A.5.5 0 0 1 14 17.5l.008-.09A.5.5 0 0 1 14.5 17h4.789l-1.646-1.646l-.058-.07a.5.5 0 0 1 .765-.638l2.516 2.517l.05.066l.035.061l.029.08l.014.086l-.002.11l-.019.085l-.023.059l-.044.077l-.04.05z");
}

</style>

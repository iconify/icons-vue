<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="raojjkbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:subtitles-sharp" /></template>
<style>
.raojjkbfc {
  fill: currentColor;
  d: path("M3 19V5h18v14zm3.577-3.577h7.846v-1H6.577zm9.846 0h1v-1h-1zm-9.846-3.577h1v-1h-1zm3 0h7.846v-1H9.577z");
}

</style>

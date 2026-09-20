<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uo2zm2b2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:upgrade-outline" /></template>
<style>
.uo2zm2b2t {
  fill: currentColor;
  d: path("M7 20v-2h10v2zm4-4V7.825L8.4 10.4L7 9l5-5l5 5l-1.4 1.4L13 7.825V16z");
}

</style>

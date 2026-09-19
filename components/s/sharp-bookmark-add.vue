<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dec50nb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-bookmark-add" /></template>
<style>
.dec50nb_m {
  fill: currentColor;
  d: path("M21 7h-2v2h-2V7h-2V5h2V3h2v2h2zm-2 14l-7-3l-7 3V3h9a5.002 5.002 0 0 0 5 7.9z");
}

</style>

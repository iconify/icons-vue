<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pkfj95bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:moviebox-alt" /></template>
<style>
.pkfj95bll {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.993 9.009c-7.815 0-6.885 33.491-19.458 33.491S1.83 5.5 9.17 5.5s13.078 22.966 23.285 22.966S44.894 9.01 38.993 9.01Z");
}

</style>

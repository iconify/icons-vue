<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gn8dy894d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:moon-fill-sharp" /></template>
<style>
.gn8dy894d {
  fill: currentColor;
  d: path("M21.214 15.893c-2.15 5.087-8.018 7.468-13.106 5.319S.637 13.195 2.786 8.107A9.99 9.99 0 0 1 12 2a1 1 0 0 1 .625 1.781a5.403 5.403 0 1 0 7.594 7.594A1.002 1.002 0 0 1 22 12a9.9 9.9 0 0 1-.786 3.893");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s73-_camz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:save-sharp" /></template>
<style>
.s73-_camz {
  fill: currentColor;
  d: path("M21 7v14H3V3h14zm-6.875 10.125Q15 16.25 15 15t-.875-2.125T12 12t-2.125.875T9 15t.875 2.125T12 18t2.125-.875M6 10h9V6H6z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="vnr0p_00j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-add-28-filled" /></template>
<style>
.vnr0p_00j {
  fill: currentColor;
  d: path("M20.5 14a6.5 6.5 0 1 1 0 13a6.5 6.5 0 0 1 0-13m0 2a.5.5 0 0 0-.5.5V20h-3.5a.5.5 0 0 0 0 1H20v3.5a.5.5 0 0 0 1 0V21h3.5a.5.5 0 0 0 0-1H21v-3.5a.5.5 0 0 0-.5-.5M21 4a1 1 0 0 1 1 1v3a1 1 0 1 1-2 0V6h-6v10.76a7.46 7.46 0 0 0-1 3.74c0 1.264.314 2.455.866 3.5H11a1 1 0 1 1 0-2h1V6H6v2a1 1 0 0 1-2 0V5a1 1 0 0 1 1-1z");
}

</style>

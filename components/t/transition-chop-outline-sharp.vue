<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iideafbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:transition-chop-outline-sharp" /></template>
<style>
.iideafbvu {
  fill: currentColor;
  d: path("M3 19V5h18v14zm1-1.815l12.185-3.212L14.119 6H4zm.817.815H20V6h-4.844l2.248 8.692zM4 6");
}

</style>

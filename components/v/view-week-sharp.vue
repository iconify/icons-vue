<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igiik9b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-week-sharp" /></template>
<style>
.igiik9b-m {
  fill: currentColor;
  d: path("M3 19V5h5.325v14zm6.33 0V5h5.345v14zm6.345 0V5H21v14z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvuv6mfzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:vignette-2-sharp" /></template>
<style>
.pvuv6mfzl {
  fill: currentColor;
  d: path("M3 21V3h18v18zm13.25-4.75Q18 14.5 18 12t-1.75-4.25T12 6T7.75 7.75T6 12t1.75 4.25T12 18t4.25-1.75");
}

</style>

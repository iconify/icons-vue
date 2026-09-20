<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_2trb_au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:volcano-outline" /></template>
<style>
.r_2trb_au {
  fill: currentColor;
  d: path("m3.539 21l3.115-7h3.019l2-5h5.577l3.423 12zm1.536-1H19.35L16.5 10h-4.15l-2 5H7.3zm8.81-14.73v-3h1v3zm4.024 1.663l-.688-.689l2.114-2.113l.713.688zm-7.05 0L8.747 4.819l.688-.713l2.114 2.138zM19.35 20H5.075z");
}

</style>

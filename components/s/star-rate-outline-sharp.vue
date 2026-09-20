<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_0o8eo1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:star-rate-outline-sharp" /></template>
<style>
.p_0o8eo1b {
  fill: currentColor;
  d: path("M9.6 15.65L12 13.8l2.4 1.85l-.9-3.05l2.25-1.6h-2.8L12 7.9l-.95 3.1h-2.8l2.25 1.6zm-1.91 2.696l1.614-5.33L5.115 10h5.216L12 4.462L13.67 10h5.215l-4.189 3.016l1.614 5.33L12 15.07zM12 11.775");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x_8z0oszt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-search-sharp-fill" /></template>
<style>
.x_8z0oszt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 2H21C21.552 2 22 2.4477 22 3V21C22 21.5523 21.552 22 21 22H3C2.448 22 2 21.5523 2 21V3C2 2.4477 2.448 2 3 2ZM13.308 14.7218L15.828 17.2426L17.243 15.8284L14.722 13.3076C15.125 12.653 15.357 11.8822 15.357 11.0572C15.357 8.6824 13.432 6.7574 11.057 6.7574C9.87 6.7574 8.794 7.2397 8.017 8.0168C7.24 8.7938 6.757 9.8701 6.757 11.0572C6.757 13.4319 8.682 15.357 11.057 15.357C11.882 15.357 12.653 15.1246 13.308 14.7218Z");
}

</style>

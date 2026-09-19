<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrjeg0bvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-satellite" /></template>
<style>
.wrjeg0bvc {
  fill: currentColor;
  d: path("M21 3H3v18h18zM5 4.99h3C8 6.65 6.66 8 5 8zM5 12v-2c2.76 0 5-2.25 5-5.01h2C12 8.86 8.87 12 5 12m0 6l3.5-4.5l2.5 3.01L14.5 12l4.5 6z");
}

</style>

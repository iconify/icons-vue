<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="px4lp1bni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shadow-minus-outline-sharp" /></template>
<style>
.px4lp1bni {
  fill: currentColor;
  d: path("M3 21V7h3.616V3H21v14.385h-4V21zm4.616-4.615H20V4H7.616zM10.5 10.5v-1h7v1z");
}

</style>

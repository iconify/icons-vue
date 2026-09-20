<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7arotboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:monitor-heart-sharp" /></template>
<style>
.h7arotboj {
  fill: currentColor;
  d: path("M3 11.5V5h18v6.5h-4.683l-1.911-3.804h-.812L10 14.866L8.317 11.5zM3 19v-6.5h4.683l1.911 3.804h.812L14 9.134l1.683 3.366H21V19z");
}

</style>

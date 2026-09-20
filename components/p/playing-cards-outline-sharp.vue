<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3qjs2buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:playing-cards-outline-sharp" /></template>
<style>
.b3qjs2buu {
  fill: currentColor;
  d: path("m15.2 14.8l1.15-4.15L12.8 8.2l-1.15 4.15zM4 18.825l-2.65-1.25L4 11.85zM6 21v-8l2.9 8zm5.25.575L5.425 5.55L16.75 1.425l5.825 16.025zM12.45 19L20 16.25L15.525 4L8 6.75zM14 11.5");
}

</style>

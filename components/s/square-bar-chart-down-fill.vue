<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v6jwl8b4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-bar-chart-down-fill" /></template>
<style>
.v6jwl8b4l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 6C2 3.79086 3.79086 2 6 2H18C20.2091 2 22 3.79086 22 6V18C22 20.2091 20.2091 22 18 22H6C3.79086 22 2 20.2091 2 18V6ZM7 8C7 7.4477 7.4477 7 8 7C8.5523 7 9 7.4477 9 8L9 13.3333C9 13.8856 8.5523 14.3333 8 14.3333C7.4477 14.3333 7 13.8856 7 13.3333ZM11 8C11 7.4477 11.4477 7 12 7C12.5523 7 13 7.4477 13 8L13 16C13 16.5523 12.5523 17 12 17C11.4477 17 11 16.5523 11 16ZM15 8C15 7.4477 15.4477 7 16 7C16.5523 7 17 7.4477 17 8L17 10.6667C17 11.219 16.5523 11.6667 16 11.6667C15.4477 11.6667 15 11.219 15 10.6667Z");
}

</style>

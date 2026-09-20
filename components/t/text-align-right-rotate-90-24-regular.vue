<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="su4xlda9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-right-rotate-90-24-regular" /></template>
<style>
.su4xlda9k {
  fill: currentColor;
  d: path("M18.25 5a.75.75 0 0 1 .75.75v15.5a.75.75 0 0 1-1.5 0V5.75a.75.75 0 0 1 .75-.75m-13 5a.75.75 0 0 1 .75.75v10.5a.75.75 0 0 1-1.5 0v-10.5a.75.75 0 0 1 .75-.75m7.25-7.25a.75.75 0 0 0-1.5 0v18.5a.75.75 0 0 0 1.5 0z");
}

</style>

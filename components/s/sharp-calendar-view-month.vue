<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfxib686h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-calendar-view-month" /></template>
<style>
.cfxib686h {
  fill: currentColor;
  d: path("M22 4H2v16h20zM8 11H4V6h4zm6 0h-4V6h4zm6 0h-4V6h4zM8 18H4v-5h4zm6 0h-4v-5h4zm6 0h-4v-5h4z");
}

</style>

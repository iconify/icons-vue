<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wexfvwbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-calendar-view-month" /></template>
<style>
.wexfvwbxs {
  fill: currentColor;
  d: path("M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2M8 11H4V6h4zm6 0h-4V6h4zm6 0h-4V6h4zM8 18H4v-5h4zm6 0h-4v-5h4zm6 0h-4v-5h4z");
}

</style>

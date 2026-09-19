<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqf2hfhaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-forward" /></template>
<style>
.dqf2hfhaf {
  fill: currentColor;
  d: path("M14 8.83L17.17 12L14 15.17V14H6v-4h8zM12 4v4H4v8h8v4l8-8z");
}

</style>

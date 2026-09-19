<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc48eknmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-turn-slight-left" /></template>
<style>
.yc48eknmu {
  fill: currentColor;
  d: path("M11.66 6V4H6v5.66h2V7.41l5 5V20h2v-7.58c0-.53-.21-1.04-.59-1.41l-5-5h2.25z");
}

</style>

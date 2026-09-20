<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="jye4zmbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:toggle-right-28-filled" /></template>
<style>
.jye4zmbqs {
  fill: currentColor;
  d: path("M26 14a6 6 0 0 0-6-6H8a6 6 0 0 0 0 12h12a6 6 0 0 0 6-6m-7 3a3 3 0 1 1 0-6a3 3 0 0 1 0 6");
}

</style>

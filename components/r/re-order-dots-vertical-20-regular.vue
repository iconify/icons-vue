<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ze9fttenn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:re-order-dots-vertical-20-regular" /></template>
<style>
.ze9fttenn {
  fill: currentColor;
  d: path("M7 5a1 1 0 1 0 0-2a1 1 0 0 0 0 2m0 6a1 1 0 1 0 0-2a1 1 0 0 0 0 2m1 5a1 1 0 1 1-2 0a1 1 0 0 1 2 0m5-11a1 1 0 1 0 0-2a1 1 0 0 0 0 2m1 5a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-1 7a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bji52eost"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:previous-frame-24-filled" /></template>
<style>
.bji52eost {
  fill: currentColor;
  d: path("M18.5 3.75a.75.75 0 0 1 1.5 0v16.5a.75.75 0 0 1-1.5 0zm-6.239-.44c1.162-.796 2.74.035 2.74 1.443v14.495c0 1.413-1.59 2.244-2.75 1.437L1.753 13.383a1.75 1.75 0 0 1 .01-2.88z");
}

</style>

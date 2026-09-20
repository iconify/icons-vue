<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ultc179yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stacks-sharp" /></template>
<style>
.ultc179yd {
  fill: currentColor;
  d: path("M12 13.385L2.02 8.192L12 3l10 5.192zm0 3.807l-9.406-4.886l1.043-.573L12 16.052l8.383-4.32l1.042.574zM12 21l-9.406-4.887l1.043-.573L12 19.86l8.383-4.32l1.042.573z");
}

</style>

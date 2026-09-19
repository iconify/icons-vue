<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zuepjb6mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-format-paint" /></template>
<style>
.zuepjb6mc {
  fill: currentColor;
  d: path("M18 4V2H4v6h14V6h1v4H9v12h4V12h8V4z");
}

</style>

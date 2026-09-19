<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq1pqjb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-bookmark-added" /></template>
<style>
.wq1pqjb6z {
  fill: currentColor;
  d: path("M17 11v6.97l-5-2.14l-5 2.14V5h6V3H7c-1.1 0-2 .9-2 2v16l7-3l7 3V11zm.83-2L15 6.17l1.41-1.41l1.41 1.41l3.54-3.54l1.41 1.41z");
}

</style>

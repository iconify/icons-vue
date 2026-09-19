<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sajzmmbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-local-hospital" /></template>
<style>
.sajzmmbry {
  fill: currentColor;
  d: path("M21 3H3.01L3 21h18zm-3 11h-4v4h-4v-4H6v-4h4V6h4v4h4z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pffl33b1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-filter-list" /></template>
<style>
.pffl33b1v {
  fill: currentColor;
  d: path("M10 18h4v-2h-4zM3 6v2h18V6zm3 7h12v-2H6z");
}

</style>

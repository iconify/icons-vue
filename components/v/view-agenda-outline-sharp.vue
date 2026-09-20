<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkyk0ubzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-agenda-outline-sharp" /></template>
<style>
.fkyk0ubzl {
  fill: currentColor;
  d: path("M3 21v-8h18v8zm2-2h14v-4H5zm-2-8V3h18v8zm2-2h14V5H5zm0 6v4zM5 5v4z");
}

</style>

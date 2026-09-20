<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yg1bmcl7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:table-sharp" /></template>
<style>
.yg1bmcl7b {
  fill: currentColor;
  d: path("M11 16H3v5h8zm2 0v5h8v-5zm-2-2V9H3v5zm2 0h8V9h-8zM3 7h18V3H3z");
}

</style>

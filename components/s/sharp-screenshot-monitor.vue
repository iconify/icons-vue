<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0xmiylwe"/><path class="zo8yn6dto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-screenshot-monitor" /></template>
<style>
.r0xmiylwe {
  fill: currentColor;
  d: path("M22 3H2v16h6v2h8v-2h6zm-2 14H4V5h16z");
}

.zo8yn6dto {
  fill: currentColor;
  d: path("M6.5 7.5H9V6H5v4h1.5zM19 12h-1.5v2.5H15V16h4z");
}

</style>

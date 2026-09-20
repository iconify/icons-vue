<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gies4oixi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:power-20-filled" /></template>
<style>
.gies4oixi {
  fill: currentColor;
  d: path("M10.75 2.5a.75.75 0 0 0-1.5 0v6a.75.75 0 0 0 1.5 0zM13.743 4a.75.75 0 1 0-.748 1.3A6 6 0 1 1 7 5.305a.75.75 0 1 0-.75-1.3a7.5 7.5 0 1 0 7.493-.003");
}

</style>

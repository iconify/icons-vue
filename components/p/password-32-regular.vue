<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lv5zpc63y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:password-32-regular" /></template>
<style>
.lv5zpc63y {
  fill: currentColor;
  d: path("M6.5 6A4.5 4.5 0 0 0 2 10.5v11A4.5 4.5 0 0 0 6.5 26h19a4.5 4.5 0 0 0 4.5-4.5v-11A4.5 4.5 0 0 0 25.5 6zM4 10.5A2.5 2.5 0 0 1 6.5 8h19a2.5 2.5 0 0 1 2.5 2.5v11a2.5 2.5 0 0 1-2.5 2.5h-19A2.5 2.5 0 0 1 4 21.5zm3.707 2.793a1 1 0 0 0-1.414 1.414L7.586 16l-1.293 1.293a1 1 0 1 0 1.414 1.414L9 17.414l1.293 1.293a1 1 0 0 0 1.414-1.414L10.414 16l1.293-1.293a1 1 0 0 0-1.414-1.414L9 14.586zm6.086 0a1 1 0 0 1 1.414 0l1.293 1.293l1.293-1.293a1 1 0 0 1 1.414 1.414L17.914 16l1.293 1.293a1 1 0 0 1-1.414 1.414L16.5 17.414l-1.293 1.293a1 1 0 0 1-1.414-1.414L15.086 16l-1.293-1.293a1 1 0 0 1 0-1.414M22 17a1 1 0 1 0 0 2h3a1 1 0 1 0 0-2z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhdunac-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pause-fill" /></template>
<style>
.xhdunac-e {
  fill: currentColor;
  d: path("M4 5C4 3.895431 4.895431 3 6 3L8 3C9.104569 3 10 3.895431 10 5L10 19C10 20.104569 9.104569 21 8 21L6 21C4.895431 21 4 20.104569 4 19ZM14 5C14 3.895431 14.895431 3 16 3L18 3C19.104569 3 20 3.895431 20 5L20 19C20 20.104569 19.104569 21 18 21L16 21C14.895431 21 14 20.104569 14 19Z");
}

</style>

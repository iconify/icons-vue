<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rawqa4bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-open-with" /></template>
<style>
.rawqa4bii {
  fill: currentColor;
  d: path("M10 9h4V6h3l-5-5l-5 5h3zm-1 1H6V7l-5 5l5 5v-3h3zm14 2l-5-5v3h-3v4h3v3zm-9 3h-4v3H7l5 5l5-5h-3z");
}

</style>

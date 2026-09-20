<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ijgs3zbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:quiz-new-20-filled" /></template>
<style>
.ijgs3zbxy {
  fill: currentColor;
  d: path("M14.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M14 3a3 3 0 0 1 3 3v3.6A5.5 5.5 0 0 0 9.602 12H5.5a.5.5 0 0 0 0 1h3.708a5.5 5.5 0 0 0-.185 1H5.5a.5.5 0 0 0 0 1h3.523c.065.715.267 1.39.579 2H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3zm.5 9a.5.5 0 0 0-.5.5V14h-1.5a.5.5 0 0 0 0 1H14v1.5a.5.5 0 0 0 1 0V15h1.5a.5.5 0 0 0 0-1H15v-1.5a.5.5 0 0 0-.5-.5M8 5a.5.5 0 0 0-.457.297l-2 4.5a.5.5 0 0 0 .914.406L6.991 9H9.01l.534 1.203a.5.5 0 0 0 .914-.406l-2-4.5A.5.5 0 0 0 8 5m5 0a.5.5 0 0 0-.5.5v1h-1a.5.5 0 0 0 0 1h1v1a.5.5 0 0 0 1 0v-1h1a.5.5 0 0 0 0-1h-1v-1A.5.5 0 0 0 13 5M8.563 8H7.437L8 6.731z");
}

</style>

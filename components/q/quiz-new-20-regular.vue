<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ojtq-me-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:quiz-new-20-regular" /></template>
<style>
.ojtq-me-y {
  fill: currentColor;
  d: path("M14.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M14 3a3 3 0 0 1 3 3v3.6a5.5 5.5 0 0 0-1-.392V6a2 2 0 0 0-2-2H6a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h3.208q.149.524.394 1H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3zm.5 9a.5.5 0 0 0-.5.5V14h-1.5a.5.5 0 0 0 0 1H14v1.5a.5.5 0 0 0 1 0V15h1.5a.5.5 0 0 0 0-1H15v-1.5a.5.5 0 0 0-.5-.5m-5.477 2a5.6 5.6 0 0 0 0 1H5.5a.5.5 0 0 1 0-1zm.579-2a5.5 5.5 0 0 0-.394 1H5.5a.5.5 0 0 1 0-1zM8 5a.5.5 0 0 1 .457.297l2 4.5a.5.5 0 1 1-.914.406L9.009 9H6.99l-.534 1.203a.5.5 0 0 1-.914-.406l2-4.5A.5.5 0 0 1 8 5m5 0a.5.5 0 0 1 .5.5v1h1a.5.5 0 0 1 0 1h-1v1a.5.5 0 0 1-1 0v-1h-1a.5.5 0 0 1 0-1h1v-1A.5.5 0 0 1 13 5M7.437 8h1.126L8 6.731z");
}

</style>

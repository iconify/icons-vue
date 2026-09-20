<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="g3a4xmqgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:temperature-degree-fahrenheit-28-filled" /></template>
<style>
.g3a4xmqgs {
  fill: currentColor;
  d: path("M5 9a2 2 0 1 1 4 0a2 2 0 0 1-4 0m2-4a4 4 0 1 0 0 8a4 4 0 0 0 0-8m7 0a1 1 0 0 0-1 1v16a1 1 0 1 0 2 0v-7h7a1 1 0 1 0 0-2h-7V7h8a1 1 0 1 0 0-2z");
}

</style>

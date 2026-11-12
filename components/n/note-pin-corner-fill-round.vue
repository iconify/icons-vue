<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xu1bx9ile"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-pin-corner-fill-round" /></template>
<style>
.xu1bx9ile {
  fill: currentColor;
  d: path("M9 12v8a1 1 0 0 1-1 1a5 5 0 0 1-3.536-1.464A4.98 4.98 0 0 1 3 16V8a5 5 0 0 1 5-5h8c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 21 8a1 1 0 0 1-1 1h-8a3 3 0 0 0-3 3m11 0a1 1 0 0 1 0 2v1.586l.707.707c.311.31.456.752.382 1.186C20.928 18.428 19.898 19 19 19h-1v2a1 1 0 0 1-2 0v-2h-1c-.898 0-1.928-.572-2.089-1.521a1.34 1.34 0 0 1 .382-1.186l.707-.707V14a1 1 0 0 1 0-2Z");
}

</style>

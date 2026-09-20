<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b57zwgb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:window-column-one-fourth-left-focus-top-20-filled" /></template>
<style>
.b57zwgb2i {
  fill: currentColor;
  d: path("M5.5 3A2.5 2.5 0 0 0 3 5.5v9A2.5 2.5 0 0 0 5.5 17h9a2.5 2.5 0 0 0 2.5-2.5v-9A2.5 2.5 0 0 0 14.5 3zM4 14.5V7h2v9h-.5A1.5 1.5 0 0 1 4 14.5M7 16V7h9v7.5a1.5 1.5 0 0 1-1.5 1.5z");
}

</style>

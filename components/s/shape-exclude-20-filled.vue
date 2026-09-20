<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fpb86p7rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shape-exclude-20-filled" /></template>
<style>
.fpb86p7rh {
  fill: currentColor;
  d: path("M2 10.5v-6A2.5 2.5 0 0 1 4.5 2h6A2.5 2.5 0 0 1 13 4.5V7H9.5A2.5 2.5 0 0 0 7 9.5V13H4.5A2.5 2.5 0 0 1 2 10.5M7 13v2.5A2.5 2.5 0 0 0 9.5 18h6a2.5 2.5 0 0 0 2.5-2.5v-6A2.5 2.5 0 0 0 15.5 7H13v3.5a2.5 2.5 0 0 1-2.5 2.5z");
}

</style>

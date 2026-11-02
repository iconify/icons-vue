<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1hufhbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:signal-low-fill-sharp" /></template>
<style>
.i1hufhbrq {
  fill: currentColor;
  d: path("M9 12a1 1 0 0 1 2 0v8a1 1 0 0 1-2 0Zm-4 8v-4a1 1 0 0 1 2 0v4a1 1 0 0 1-2 0m9-1h.01a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2");
}

</style>

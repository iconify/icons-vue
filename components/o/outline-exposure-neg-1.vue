<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7geb1b7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-exposure-neg-1" /></template>
<style>
.x7geb1b7w {
  fill: currentColor;
  d: path("M4 11v2h8v-2zm15 7h-2V7.38L14 8.4V6.7L18.7 5h.3z");
}

</style>

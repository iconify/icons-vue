<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5fhr5b7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-2k" /></template>
<style>
.i5fhr5b7i {
  fill: currentColor;
  d: path("M21 3H3v18h18zM8 12.5v1h3V15H6.5v-3.5h3v-1h-3V9H11v3.5zM18 15h-1.75l-1.75-2.25V15H13V9h1.5v2.25L16.25 9H18l-2.25 3z");
}

</style>

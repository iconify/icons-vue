<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibxi-lb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-4k" /></template>
<style>
.ibxi-lb_t {
  fill: currentColor;
  d: path("M21 3H3v18h18zm-9 10.51h-1V15H9.5v-1.5h-3V9H8v3h1.5V9H11v3h1zM18.2 15h-1.7l-2-3v3H13V9h1.5v3l2-3h1.7l-2 3z");
}

</style>

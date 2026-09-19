<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l579zxbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-shopping-bag" /></template>
<style>
.l579zxbsy {
  fill: currentColor;
  d: path("M20 6h-4c0-2.21-1.79-4-4-4S8 3.79 8 6H4v16h16zm-10 5H8V8h2zm2-7c1.1 0 2 .9 2 2h-4c0-1.1.9-2 2-2m4 7h-2V8h2z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eih77bujc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-10k" /></template>
<style>
.eih77bujc {
  fill: currentColor;
  d: path("M10 10.5h1.5v3H10zM21 3H3v18h18zM7.5 15H6v-4.5H4.5V9h3zM13 9v6H8.5V9zm6 6h-1.75l-1.75-2.25V15H14V9h1.5v2.25L17.25 9H19l-2.25 3z");
}

</style>

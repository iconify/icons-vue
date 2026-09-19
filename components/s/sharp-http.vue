<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh3kz7y8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-http" /></template>
<style>
.mh3kz7y8j {
  fill: currentColor;
  d: path("M4.5 11h-2V9H1v6h1.5v-2.5h2V15H6V9H4.5zm2.5-.5h1.5V15H10v-4.5h1.5V9H7zm5.5 0H14V15h1.5v-4.5H17V9h-4.5zM23 9h-5v6h1.5v-2H23zm-1.5 2.5h-2v-1h2z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jgax-bltc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-edit-style-character-a-32-filled" /></template>
<style>
.jgax-bltc {
  fill: currentColor;
  d: path("M21.26 11.328a4.536 4.536 0 0 1 6.414 6.414l-9.417 9.418c-.48.48-1.076.831-1.73 1.018l-6.255 1.787a1 1 0 0 1-1.235-1.236l1.785-6.251a4 4 0 0 1 1.019-1.73zM9.5 2a1 1 0 0 1 .92.61l5.187 12.258l-1.526 1.527l-.002-.005L12.645 13h-6.29l-1.434 3.39a1 1 0 0 1-1.842-.78l5.5-13A1 1 0 0 1 9.5 2m-2.299 9H11.8L9.5 5.566z");
}

</style>

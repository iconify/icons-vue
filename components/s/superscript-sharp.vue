<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3ej0_l5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:superscript-sharp" /></template>
<style>
.j3ej0_l5t {
  fill: currentColor;
  d: path("M19 9V6h3V5h-3V4h4v3h-3v1h3v1zM5.875 20l4.625-7.275L6.2 6h2.65l3.1 5h.1l3.075-5H17.8l-4.325 6.725L18.125 20H15.45l-3.4-5.425h-.1L8.55 20z");
}

</style>

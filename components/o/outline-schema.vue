<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b809c7-4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-schema" /></template>
<style>
.b809c7-4z {
  fill: currentColor;
  d: path("M14 9v2h-3V9H8.5V7H11V1H4v6h2.5v2H4v6h2.5v2H4v6h7v-6H8.5v-2H11v-2h3v2h7V9zM6 3h3v2H6zm3 18H6v-2h3zm0-8H6v-2h3zm10 0h-3v-2h3z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3nyhxbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:thumb-up-outline-sharp" /></template>
<style>
.e3nyhxbrb {
  fill: currentColor;
  d: path("M7 21V8l7-7l1.85 1.85L14.55 8H23v4.4L19.35 21zm2-2h9l3-7v-2h-9l1.35-5.5L9 8.85zM9 8.85V19zM2 21V8h5v2H4v9h3v2z");
}

</style>

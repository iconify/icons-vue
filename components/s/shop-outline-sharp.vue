<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbvkzcb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shop-outline-sharp" /></template>
<style>
.xbvkzcb9h {
  fill: currentColor;
  d: path("M2 21V6h6V2h8v4h6v15zm2-2h16V8H4zm6-13h4V4h-4zM4 19V8zm5.5-1l7-4.5l-7-4.5z");
}

</style>

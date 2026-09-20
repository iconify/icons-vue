<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkmee3bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:width-wide-outline-sharp" /></template>
<style>
.jkmee3bvw {
  fill: currentColor;
  d: path("M3 19V5h18v14zm1-1h3V6H4zm4 0h8V6H8zm9 0h3V6h-3zM8 6v12z");
}

</style>

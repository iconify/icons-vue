<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tos_zrqmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:wifi-1-bar-outline-sharp" /></template>
<style>
.tos_zrqmn {
  fill: currentColor;
  d: path("m12 21l-3.525-3.55q.7-.7 1.613-1.075T12 16t1.913.375t1.612 1.075z");
}

</style>

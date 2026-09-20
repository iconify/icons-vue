<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9vbty18h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pergola-outline-sharp" /></template>
<style>
.b9vbty18h {
  fill: currentColor;
  d: path("M4 20V3h1v2h14V3h1v17h-1V9.77H5V20zM5 8.77h14V6H5zM11.5 20v-2.827H8.673v-1h6.635v1H12.5V20zM5 8.77V6z");
}

</style>

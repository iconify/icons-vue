<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_vgzxvyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mirror-stack-outline-sharp" /></template>
<style>
.d_vgzxvyz {
  fill: currentColor;
  d: path("M14 18v-2h4V4h-6v2.25h-2V2h10v16zm-8 2h6V8H6zm-2 2V6h10v16zm2-2V8zM18 4v12z");
}

</style>

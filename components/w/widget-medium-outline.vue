<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gl4bdsb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:widget-medium-outline" /></template>
<style>
.gl4bdsb9c {
  fill: currentColor;
  d: path("M2 22v-6h6v6zm7 0v-6h6v6zm7 0v-6h6v6zM2 15V9h6v6zm7 0V9h6v6zm7 0V9h6v6zM2 8V2h13v6zm14 0V2h6v6zm-5 10h2zm-5-5v-2zm12 0v-2zM4 20h2v-2H4zm7 0h2v-2h-2zm7 0h2v-2h-2zM4 13h2v-2H4zm7 0h2v-2h-2zm7 0h2v-2h-2zm0-7h2V4h-2z");
}

</style>

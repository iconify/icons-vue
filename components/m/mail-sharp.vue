<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bf4t9pbre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mail-sharp" /></template>
<style>
.bf4t9pbre {
  fill: currentColor;
  d: path("M2 20V4h20v16zm10-7l8-5V6l-8 5l-8-5v2z");
}

</style>

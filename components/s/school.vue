<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx7oh-baa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:school" /></template>
<style>
.zx7oh-baa {
  fill: currentColor;
  d: path("M21 17v-6.9L12 15L1 9l11-6l11 6v8zm-9 4l-7-3.8v-5l7 3.8l7-3.8v5z");
}

</style>

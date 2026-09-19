<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzvno1w7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-email" /></template>
<style>
.uzvno1w7h {
  fill: currentColor;
  d: path("M22 4H2v16h20zm-2 4l-8 5l-8-5V6l8 5l8-5z");
}

</style>

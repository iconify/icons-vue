<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mq5p0e3-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-laptop-windows" /></template>
<style>
.mq5p0e3-g {
  fill: currentColor;
  d: path("M20 18v-1h1.99L22 3H2v14h2v1H0v2h24v-2zM4 5h16v10H4z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufifh5b_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-screen-rotation-alt" /></template>
<style>
.ufifh5b_n {
  fill: currentColor;
  d: path("m4 7.59l5-5c.78-.78 2.05-.78 2.83 0L20.24 11h-2.83L10.4 4L5.41 9H8v2H2V5h2zM20 19h2v-6h-6v2h2.59l-4.99 5l-7.01-7H3.76l8.41 8.41c.78.78 2.05.78 2.83 0l5-5z");
}

</style>

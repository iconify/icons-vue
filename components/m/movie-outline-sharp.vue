<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbnn7zbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:movie-outline-sharp" /></template>
<style>
.sbnn7zbtr {
  fill: currentColor;
  d: path("M2 20V4h2l2 4h3L7 4h2l2 4h3l-2-4h2l2 4h3l-2-4h5v16zm2-10v8h16v-8zm0 0v8z");
}

</style>

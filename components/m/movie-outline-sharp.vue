<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f54_s7chs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:movie-outline-sharp" /></template>
<style>
.f54_s7chs {
  fill: currentColor;
  d: path("M3 19V5h1.616l1.5 3h3l-1.5-3h2l1.5 3h3l-1.5-3h2l1.5 3h3l-1.5-3H21v14zM4 9v9h16V9zm0 0v9z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3d1z13kv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:movie-off-outline-sharp" /></template>
<style>
.a3d1z13kv {
  fill: currentColor;
  d: path("M3 19V5h1.808l4 4H4v9h13.808l1 1zm18-.644l-1-1V9h-8.361l-4-4h1.419l1.425 2.844l.156.156h2.919l-1.5-3h2.5l1.5 3h3l-1.5-3H21zm-1.09 3.173L2.47 4.09l.714-.714l17.438 17.439zm-4.081-8.152");
}

</style>

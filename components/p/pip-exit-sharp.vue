<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op9xnsa6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pip-exit-sharp" /></template>
<style>
.op9xnsa6r {
  fill: currentColor;
  d: path("M3 19v-7.77h8.23V5H21v14zm14.267-3l.714-.713L13.669 11h3.312v-1h-5v5h1v-3.286zM3 8.846V5h5.846v3.846z");
}

</style>

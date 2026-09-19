<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="woje_d01k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-drag-handle" /></template>
<style>
.woje_d01k {
  fill: currentColor;
  d: path("M20 9H4v2h16zM4 15h16v-2H4z");
}

</style>

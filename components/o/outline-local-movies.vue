<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzdkpcbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-local-movies" /></template>
<style>
.zzdkpcbhn {
  fill: currentColor;
  d: path("M14 5v14h-4V5zm6-2h-2v2h-2V3H8v2H6V3H4v18h2v-2h2v2h8v-2h2v2h2zm-4 6V7h2v2zM6 9V7h2v2zm10 4v-2h2v2zM6 13v-2h2v2zm10 4v-2h2v2zM6 17v-2h2v2z");
}

</style>

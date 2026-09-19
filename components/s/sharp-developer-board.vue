<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynhs937hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-developer-board" /></template>
<style>
.ynhs937hn {
  fill: currentColor;
  d: path("M22 9V7h-2V3H2v18h18v-4h2v-2h-2v-2h2v-2h-2V9zm-4 10H4V5h14zM6 13h5v4H6zm6-6h4v3h-4zM6 7h5v5H6zm6 4h4v6h-4z");
}

</style>

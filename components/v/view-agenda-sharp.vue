<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="leprq-4jz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-agenda-sharp" /></template>
<style>
.leprq-4jz {
  fill: currentColor;
  d: path("M3 21v-8h18v8zm0-10V3h18v8z");
}

</style>

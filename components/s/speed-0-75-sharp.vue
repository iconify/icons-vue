<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vikvaq5nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speed-0-75-sharp" /></template>
<style>
.vikvaq5nj {
  fill: currentColor;
  d: path("M5 17v-2h2v2zm9 0v-2h4v-2h-4V7h6v2h-4v2h4v6zm-5 0l2-8H7V7h6v1.8L11 17z");
}

</style>

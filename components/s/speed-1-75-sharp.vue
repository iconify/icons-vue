<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7lu3oukv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speed-1-75-sharp" /></template>
<style>
.w7lu3oukv {
  fill: currentColor;
  d: path("M7 17v-2h2v2zm9 0v-2h4v-2h-4V7h6v2h-4v2h4v6zM4 17V9H2V7h4v10zm7 0l2-8H9V7h6.05v1.85L13 17z");
}

</style>

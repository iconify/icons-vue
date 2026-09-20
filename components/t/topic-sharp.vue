<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lb2m62zlj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:topic-sharp" /></template>
<style>
.lb2m62zlj {
  fill: currentColor;
  d: path("M3 19V5h6.596l2 2H21v12zm3.5-3.5h7v-1h-7zm0-4h11v-1h-11z");
}

</style>

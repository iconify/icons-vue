<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmogtbcev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:print-portrait-long-outline-sharp" /></template>
<style>
.bmogtbcev {
  fill: currentColor;
  d: path("M13 20v-2h4V5H6.35V3H19v17zM4 10V7h1V3.95L6.35 3L14 5.775V21.4l-1.35.95L5 19.575V17H4v-3h1v-4zm3-4.675v12.85l5 1.8V7.15zM17 18V4.275zm-10 .175V5.325z");
}

</style>

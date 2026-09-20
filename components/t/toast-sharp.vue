<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znnsddche"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:toast-sharp" /></template>
<style>
.znnsddche {
  fill: currentColor;
  d: path("M6 18h12v-2H6zm-3 3V3h18v18z");
}

</style>

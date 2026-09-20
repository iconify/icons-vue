<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4d7iwbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:thumb-down-sharp" /></template>
<style>
.s4d7iwbmc {
  fill: currentColor;
  d: path("M1 16v-4.4L4.65 3H16v13l-7 7l-1.85-1.85L8.45 16zm17 0V3h4v13z");
}

</style>

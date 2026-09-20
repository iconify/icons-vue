<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxg571b9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:newsmode-sharp" /></template>
<style>
.jxg571b9c {
  fill: currentColor;
  d: path("M2 21V3h20v18zm4-4h12v-2H6zm0-4h4V7H6zm6 0h6v-2h-6zm0-4h6V7h-6z");
}

</style>

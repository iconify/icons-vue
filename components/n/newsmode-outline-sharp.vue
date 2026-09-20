<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5mpjsbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:newsmode-outline-sharp" /></template>
<style>
.a5mpjsbie {
  fill: currentColor;
  d: path("M2 21V3h20v18zm2-2h16V5H4zm2-2h12v-2H6zm0-4h4V7H6zm6 0h6v-2h-6zm0-4h6V7h-6zM4 19V5z");
}

</style>

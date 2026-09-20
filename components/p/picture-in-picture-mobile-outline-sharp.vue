<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pc32ukbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:picture-in-picture-mobile-outline-sharp" /></template>
<style>
.pc32ukbhp {
  fill: currentColor;
  d: path("M20 22H4V2h16zm-2-2V4H6v16zm0-16H6zm-1 9V5h-6v8zm-2-2h-2V7h2z");
}

</style>

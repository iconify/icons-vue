<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5w6tdb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:meter-fill-round" /></template>
<style>
.q5w6tdb0y {
  fill: currentColor;
  d: path("M15 3a1 1 0 0 1 2 0a5 5 0 0 1 5 5v9a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5a1 1 0 0 1 2 0ZM7 7v3a1 1 0 0 0 2 0V7a1 1 0 0 0-2 0m4 0v3a1 1 0 0 0 2 0V7a1 1 0 0 0-2 0m4 0v3a1 1 0 0 0 2 0V7a1 1 0 0 0-2 0m1 9H8a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2");
}

</style>

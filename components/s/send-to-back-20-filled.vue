<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f9o5r5bnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:send-to-back-20-filled" /></template>
<style>
.f9o5r5bnl {
  fill: currentColor;
  d: path("M12 14a2 2 0 0 1 2-2h3a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2h-3a2 2 0 0 1-2-2zm2-1a1 1 0 0 0-1 1v3a1 1 0 0 0 1 1h3a1 1 0 0 0 1-1v-3a1 1 0 0 0-1-1zM5 9h1.3A2.7 2.7 0 0 0 9 6.3V5h3.5A2.5 2.5 0 0 1 15 7.5V11h-1.3a2.7 2.7 0 0 0-2.7 2.7V15H7.5A2.5 2.5 0 0 1 5 12.5zM1 3a2 2 0 0 1 2-2h3a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2zm2-1a1 1 0 0 0-1 1v3a1 1 0 0 0 1 1h3a1 1 0 0 0 1-1V3a1 1 0 0 0-1-1z");
}

</style>

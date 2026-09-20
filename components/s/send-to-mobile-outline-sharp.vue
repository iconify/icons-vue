<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw8lvvxuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:send-to-mobile-outline-sharp" /></template>
<style>
.qw8lvvxuc {
  fill: currentColor;
  d: path("M8 11v2h4.15l-1.55 1.6L12 16l4-4l-4-4l-1.4 1.4l1.55 1.6zM5 23V1h14v5.1h1v4.8h-1V23zm2-2h10V3H7zm0 0V3z");
}

</style>

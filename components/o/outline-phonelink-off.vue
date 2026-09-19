<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejkeb2cdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-phonelink-off" /></template>
<style>
.ejkeb2cdl {
  fill: currentColor;
  d: path("M22 6V4H7.39l2 2zm2 13V9c0-.55-.45-1-1-1h-6c-.55 0-1 .45-1 1v3.61l2 2V10h4v7h-1.61l2.93 2.93c.39-.13.68-.49.68-.93M2.06 1.51L.65 2.92l1.82 1.82C2.18 5.08 2 5.52 2 6v11H0v3h17.73l2.35 2.35l1.41-1.41zM4 17V6.27L14.73 17z");
}

</style>

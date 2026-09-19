<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phy25iykj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-view-kanban" /></template>
<style>
.phy25iykj {
  fill: currentColor;
  d: path("M21 3H3v18h18zM9 17H7V7h2zm4-5h-2V7h2zm4 3h-2V7h2z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="p7xtq_bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:send-clock-28-regular" /></template>
<style>
.p7xtq_bko {
  fill: currentColor;
  d: path("M20.5 14a6.5 6.5 0 1 1 0 13a6.5 6.5 0 0 1 0-13M2.044 4.077c-.275-1.03.783-1.911 1.746-1.453l21.497 10.25c.85.405.937 1.527.265 2.083a7.5 7.5 0 0 0-2.672-1.569L3.633 4.212l2.418 9.04h11.2c.22 0 .416.097.553.248c-.778.3-1.493.726-2.12 1.252H6.05l-2.418 9.04L13.1 19.28a7.6 7.6 0 0 0-.084 1.7l-9.226 4.4c-.963.459-2.02-.42-1.746-1.45L4.7 14.001zM20.5 16.5a.5.5 0 0 0-.5.5v3.5a.5.5 0 0 0 .5.5h3a.5.5 0 0 0 0-1H21v-3a.5.5 0 0 0-.5-.5");
}

</style>

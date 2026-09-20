<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c89gtac8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-desktop-16-filled" /></template>
<style>
.c89gtac8c {
  fill: currentColor;
  d: path("M6 1a2 2 0 0 0-2 2v2h1.5A2.5 2.5 0 0 1 8 7.5V11h2v1H8v1h3.5a.5.5 0 0 0 0-1H11v-1h2a2 2 0 0 0 2-2V3a2 2 0 0 0-2-2zM2.5 6A1.5 1.5 0 0 0 1 7.5v6A1.5 1.5 0 0 0 2.5 15h3A1.5 1.5 0 0 0 7 13.5v-6A1.5 1.5 0 0 0 5.5 6zm.5 6.5a.5.5 0 0 1 .5-.5h1a.5.5 0 0 1 0 1h-1a.5.5 0 0 1-.5-.5");
}

</style>

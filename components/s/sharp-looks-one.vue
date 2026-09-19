<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6as2zbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-looks-one" /></template>
<style>
.a6as2zbqa {
  fill: currentColor;
  d: path("M21 3H3v18h18zm-7 14h-2V9h-2V7h4z");
}

</style>

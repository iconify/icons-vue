<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj5a0g84b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-keyboard-tab" /></template>
<style>
.rj5a0g84b {
  fill: currentColor;
  d: path("M11.59 7.41L15.17 11H1v2h14.17l-3.59 3.59L13 18l6-6l-6-6zM20 6v12h2V6z");
}

</style>

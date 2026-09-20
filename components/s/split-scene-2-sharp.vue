<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg5nmnbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:split-scene-2-sharp" /></template>
<style>
.bg5nmnbrk {
  fill: currentColor;
  d: path("M5 20v-5.115h14V20zm-2-7.5v-1h2V4h14v7.5h2v1z");
}

</style>

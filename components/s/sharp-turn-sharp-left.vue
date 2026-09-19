<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvpj29bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-turn-sharp-left" /></template>
<style>
.dvpj29bcp {
  fill: currentColor;
  d: path("M6 6.83L4.41 8.41L3 7l4-4l4 4l-1.41 1.41L8 6.83V13h10v8h-2v-6H6z");
}

</style>

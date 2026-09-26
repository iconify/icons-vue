<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hqbzs7b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:subtitles-sharp-fill" /></template>
<style>
.hqbzs7b1j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 3L22 3C22.5523 3 23 3.4477 23 4L23 20C23 20.5523 22.5523 21 22 21L2 21C1.4477 21 1 20.5523 1 20L1 4C1 3.4477 1.4477 3 2 3ZM5 11L9 11L9 9L5 9L5 11ZM11 11L19 11L19 9L11 9L11 11ZM5 15L13 15L13 13L5 13L5 15ZM15 15L19 15L19 13L15 13L15 15Z");
}

</style>

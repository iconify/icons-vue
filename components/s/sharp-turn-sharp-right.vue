<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdp-zedij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-turn-sharp-right" /></template>
<style>
.kdp-zedij {
  fill: currentColor;
  d: path("m18 6.83l1.59 1.58L21 7l-4-4l-4 4l1.41 1.41L16 6.83V13H6v8h2v-6h10z");
}

</style>

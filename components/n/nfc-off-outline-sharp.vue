<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je9wn4sjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:nfc-off-outline-sharp" /></template>
<style>
.je9wn4sjo {
  fill: currentColor;
  d: path("M3 21V5.825L.675 3.5L2.1 2.075l19.8 19.8l-1.425 1.425l-2.3-2.3zm4-4V9.825l-2-2V19h11.175l-2-2zm14 1.175l-2-2V5H7.825l-2-2H21zM9 15h3.175L9 11.825zm8-.825l-2-2V9h-2v1.175L11.125 8.3V7H17zm-3.575-3.6");
}

</style>

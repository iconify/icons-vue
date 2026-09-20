<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dozh5-9_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:text-rotation-angleup-outline-sharp" /></template>
<style>
.dozh5-9_q {
  fill: currentColor;
  d: path("m9.725 21.7l-1.4-1.4l9.3-9.3h-1.6V9h5v5h-2v-1.6zm-1.5-5.6L3.375 5.4l1.4-1.4l10.7 4.9l-1.35 1.35l-2.65-1.3l-3.15 3.15l1.25 2.65zm-.65-5.55l2.35-2.3l-4.35-2.1l-.05.05z");
}

</style>

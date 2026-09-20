<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lopfx-b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:terminal-2-sharp" /></template>
<style>
.lopfx-b4r {
  fill: currentColor;
  d: path("M12 20v-2h8v2zm-6.5-4l-1.4-1.4L8.675 10L4.1 5.4L5.5 4l6 6z");
}

</style>

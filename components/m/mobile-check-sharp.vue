<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tk52xpbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-check-sharp" /></template>
<style>
.tk52xpbjr {
  fill: currentColor;
  d: path("M11.05 15L16 10.05l-1.4-1.4l-3.55 3.55l-1.4-1.4l-1.4 1.4zM5 23V1h14v5.1h1v4.8h-1V23z");
}

</style>

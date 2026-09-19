<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4ajyobjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-colorize" /></template>
<style>
.k4ajyobjn {
  fill: currentColor;
  d: path("m21.42 6.34l-3.75-3.75l-3.82 3.82l-1.94-1.91l-1.41 1.41l1.42 1.42L3 16.25V21h4.75l8.92-8.92l1.42 1.42l1.41-1.41l-1.92-1.92zM6.92 19L5 17.08l8.06-8.06l1.92 1.92z");
}

</style>

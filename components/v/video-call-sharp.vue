<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x56bcwl_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:video-call-sharp" /></template>
<style>
.x56bcwl_f {
  fill: currentColor;
  d: path("M9 16h2v-3h3v-2h-3V8H9v3H6v2h3zm-7 4V4h16v6.5l4-4v11l-4-4V20z");
}

</style>

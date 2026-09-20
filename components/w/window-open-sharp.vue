<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo9pnmbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:window-open-sharp" /></template>
<style>
.yo9pnmbhf {
  fill: currentColor;
  d: path("M4 21V3h16v18zm3-10h4v-1h2v1h4V6H7zm-1 8h12V5H6z");
}

</style>

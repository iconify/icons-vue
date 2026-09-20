<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rli6xr67k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:picture-in-picture-outline-sharp" /></template>
<style>
.rli6xr67k {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h16V6H4zm7-5h8V7h-8zm2-2V9h4v2zm-9 7V6z");
}

</style>

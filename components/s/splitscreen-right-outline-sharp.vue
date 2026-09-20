<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zipj-761y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:splitscreen-right-outline-sharp" /></template>
<style>
.zipj-761y {
  fill: currentColor;
  d: path("M13 21V3h8v18zM3 21V3h8v18zM5 5v14h4V5z");
}

</style>

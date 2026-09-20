<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbqwdbbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:skip-next-outline" /></template>
<style>
.pbqwdbbjh {
  fill: currentColor;
  d: path("M16.5 18V6h2v12zm-11 0V6l9 6zm2-3.75L10.9 12L7.5 9.75z");
}

</style>

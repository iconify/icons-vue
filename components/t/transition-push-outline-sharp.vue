<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwenjbbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:transition-push-outline-sharp" /></template>
<style>
.fwenjbbva {
  fill: currentColor;
  d: path("M8 20v-1.975h2V6H8V4h4v16zm6 0V4h9v16zm2-1.975h5V6h-5zM5 16l-1.425-1.4L5.15 13H1v-2h4.15L3.575 9.425L5 8l4 4zm11 2.025V6z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aohd8lrit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:transition-slide-outline-sharp" /></template>
<style>
.aohd8lrit {
  fill: currentColor;
  d: path("M1 20V4h6v16zm2-1.975h2V5.975H3zM9 20V4h14v16zm2-1.975h10V5.975H11zm-6 0V5.975zm6 0V5.975z");
}

</style>

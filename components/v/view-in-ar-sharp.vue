<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ho4c3pb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-in-ar-sharp" /></template>
<style>
.ho4c3pb-w {
  fill: currentColor;
  d: path("m12 20.05l-7-4.025v-8.05l7-4.025l7 4.025v8.05zM2 7V2h5v2H4v3zm5 15H2v-5h2v3h3zm10 0v-2h3v-3h2v5zm3-15V4h-3V2h5v5zM8.05 8.525l-1.05.6v1.125l4 2.325v4.6l1 .575l1-.575v-4.6l4-2.325V9.125l-1.05-.6L12 10.85z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9lev1byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:movie-off-outline-sharp" /></template>
<style>
.t9lev1byg {
  fill: currentColor;
  d: path("M2 20V4h2l6 6H4v8h14l2 2zm20-.875l-2-2V10h-7.15l-6-6H8.5l1.675 3.325l.675.675h2.65l-2-4H14l2 4h3l-2-4h5zm-2.225 3.5l-18.4-18.4L2.8 2.8l18.4 18.4zm-3.35-9.075");
}

</style>

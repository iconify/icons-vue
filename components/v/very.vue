<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v1ijwrb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:very" /></template>
<style>
.v1ijwrb-y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.133 5.5l14.182 37l11.692-.088l9.86-25.786l-11.083-5.234l-5.02 14.879L19.4 5.5ZM25.77 26.27L20.31 42.5");
}

</style>

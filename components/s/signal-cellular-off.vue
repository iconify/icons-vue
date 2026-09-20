<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys9nsw2mn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:signal-cellular-off" /></template>
<style>
.ys9nsw2mn {
  fill: currentColor;
  d: path("m20.775 23.6l-1.6-1.6H2l8.6-8.6l-8.2-8.175L3.8 3.8l18.4 18.4zM22 19.2l-8.6-8.6L22 2z");
}

</style>

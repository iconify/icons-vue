<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw3cz61yj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:screenshot-frame-2-sharp" /></template>
<style>
.zw3cz61yj {
  fill: currentColor;
  d: path("M20 10V7h-3V5h5v5zM2 10V5h5v2H4v3zm15 9v-2h3v-3h2v5zM2 19v-5h2v3h3v2z");
}

</style>

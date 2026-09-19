<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xi9oep7-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:t-graffiti" /></template>
<style>
.xi9oep7-f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.935 12.466c25.248 9.018 37.42-1.013 33.363-5.409s-17.132 0-17.132 19.838c0 9.918 1.803 17.132 13.525 15.328");
}

</style>

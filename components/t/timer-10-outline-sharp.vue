<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2zu31-zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:timer-10-outline-sharp" /></template>
<style>
.v2zu31-zx {
  fill: currentColor;
  d: path("M14 16h3V8h-3zm-3 3V5h9v14zm-5 0V8H4V5h5v14z");
}

</style>

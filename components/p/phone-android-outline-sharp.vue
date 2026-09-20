<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg337bf4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:phone-android-outline-sharp" /></template>
<style>
.vg337bf4c {
  fill: currentColor;
  d: path("M10 20h4v-1h-4zm-5 3V1h14v22zm2-5v3h10v-3zm0-2h10V6H7zM7 4h10V3H7zm0 14v3zM7 4V3z");
}

</style>

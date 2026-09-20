<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys1vj0b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:move-selection-down-sharp" /></template>
<style>
.ys1vj0b_z {
  fill: currentColor;
  d: path("M6.962 21V10.923h10.077V21zm0-12.808v-1.23h1.23v1.23zm8.846 0v-1.23h1.23v1.23zM6.962 4.231V3h1.23v1.23zm4.423 0V3h1.23v1.23zm4.423 0V3h1.23v1.23z");
}

</style>

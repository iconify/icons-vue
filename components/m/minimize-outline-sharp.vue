<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qt2fe3thc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:minimize-outline-sharp" /></template>
<style>
.qt2fe3thc {
  fill: currentColor;
  d: path("M6.5 20v-1h11v1z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohmkwdbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:segment-sharp" /></template>
<style>
.ohmkwdbaz {
  fill: currentColor;
  d: path("M10 17.27v-1h10v1zm0-4.77v-1h10v1zM4 7.73v-1h16v1z");
}

</style>

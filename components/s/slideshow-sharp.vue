<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfasldhko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:slideshow-sharp" /></template>
<style>
.rfasldhko {
  fill: currentColor;
  d: path("m9.5 16.5l7-4.5l-7-4.5zM3 21V3h18v18z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2uusbb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:point-scan" /></template>
<style>
.x2uusbb3z {
  fill: currentColor;
  d: path("M10.934 13.066Q10.5 12.633 10.5 12t.434-1.066T12 10.5t1.066.434q.434.433.434 1.066t-.434 1.066T12 13.5t-1.066-.434M11.5 8V4h1v4zm0 12v-4h1v4zm4.5-7.5v-1h4v1zm-12 0v-1h4v1z");
}

</style>

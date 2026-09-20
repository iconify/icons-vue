<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_u-8mv8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tablet-camera-outline-sharp" /></template>
<style>
.b_u-8mv8s {
  fill: currentColor;
  d: path("M2 19V5h20v14h-3.5V6h-13v13zm1-1h1.5V6H3zm16.5 0H21V6h-1.5zM8.154 21v-5.98h2.135l.865-.866h1.692l.857.865h2.143V21zm4.9-1.945q.446-.445.446-1.058t-.445-1.045T12 16.519t-1.055.433t-.445 1.045t.445 1.058T12 19.5t1.055-.445M3 6h1.5zm16.5 0H21z");
}

</style>

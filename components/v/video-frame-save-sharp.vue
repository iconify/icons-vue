<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2ar4ibvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:video-frame-save-sharp" /></template>
<style>
.g2ar4ibvn {
  fill: currentColor;
  d: path("M20 10V6h-4V4h6v6zM2 10V4h6v2H4v4zm0 10v-6h2v4h4v2zm7.5-3.5v-9l7 4.5zm5.5 7.475v-2h8v2zM19 21l-4-4l1.4-1.4l1.6 1.55V13h2v4.15l1.6-1.55L23 17z");
}

</style>

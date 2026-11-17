<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chd1b1bwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scooter-electric-fill-round" /></template>
<style>
.chd1b1bwb {
  fill: currentColor;
  d: path("M21 5h-2.82l1.688 10.128a3 3 0 1 1-2.011.098l-.67-4.022c-.827.451-1.383 1.627-1.729 2.457c-.231.555-.432 1.124-.633 1.692c-.267.756-.524 1.531-.908 2.237c-.402.74-1.015 1.409-1.917 1.41H7.829a3 3 0 1 1 0-2h4.084c.103-.103.178-.238.247-.365c.146-.268.263-.551.373-.835c.144-.368.275-.741.406-1.114c.718-2.03 1.66-4.78 3.91-5.509l-.835-5.013A.998.998 0 0 1 17 3h4a1 1 0 0 1 0 2m-10.2-.4L9 7h2a.998.998 0 0 1 .8 1.6l-3 4a1 1 0 0 1-1.6-1.2L9 9H7a.998.998 0 0 1-.8-1.6l3-4a1 1 0 1 1 1.6 1.2M5.707 17.293a.999.999 0 1 0-1.414 1.414a.999.999 0 1 0 1.414-1.414M18 18a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o4uyombis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vip-32-light" /></template>
<style>
.o4uyombis {
  fill: currentColor;
  d: path("M25.5 4A4.5 4.5 0 0 1 30 8.5v15a4.5 4.5 0 0 1-4.5 4.5h-19A4.5 4.5 0 0 1 2 23.5v-15A4.5 4.5 0 0 1 6.5 4zm-19 1A3.5 3.5 0 0 0 3 8.5v15A3.5 3.5 0 0 0 6.5 27h19a3.5 3.5 0 0 0 3.5-3.5v-15A3.5 3.5 0 0 0 25.5 5zm7.032 6.324a.5.5 0 1 1 .936.352l-3.338 8.888a.673.673 0 0 1-1.26 0l-3.338-8.888a.5.5 0 1 1 .936-.352l3.032 8.074zM16.5 11a.5.5 0 0 1 .5.5v9a.5.5 0 0 1-1 0v-9a.5.5 0 0 1 .5-.5m6.5 0a3 3 0 1 1 0 6h-3v3.5a.5.5 0 0 1-1 0v-9a.5.5 0 0 1 .5-.5zm-3 5h3a2 2 0 1 0 0-4h-3z");
}

</style>

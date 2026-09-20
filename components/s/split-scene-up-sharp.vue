<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3qy9xntt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:split-scene-up-sharp" /></template>
<style>
.o3qy9xntt {
  fill: currentColor;
  d: path("M4 21v-6h16v6zm-2-8v-2h2V3h16v8h2v2z");
}

</style>

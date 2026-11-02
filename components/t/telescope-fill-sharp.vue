<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n96b2d6xf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:telescope-fill-sharp" /></template>
<style>
.n96b2d6xf {
  fill: currentColor;
  d: path("m16.894 8.553l-2.447-4.895l3.106-1.552a1 1 0 0 1 1.341.447l2 4a1 1 0 0 1-.447 1.341l-3.105 1.553Zm-7.13 4.683l-3.317 1.658a1 1 0 0 1-1.341-.447l-2-4a1 1 0 0 1 .447-1.341l9.105-4.553l2.895 5.789l-2.211 1.105l4.552 9.106a1 1 0 1 1-1.788.894L12 13.236l-4.106 8.211a1 1 0 1 1-1.788-.894Z");
}

</style>

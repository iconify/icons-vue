<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6ggye-ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:slab-serif-outline-sharp" /></template>
<style>
.y6ggye-ao {
  fill: currentColor;
  d: path("M5.75 18h5.15v-1.75H8.725l.775-2h4.85l.75 2h-2.125V18h5.275v-1.75h-1L13.2 6h-2.375L6.75 16.25h-1zm4.375-5.375l1.7-4.425H12l1.7 4.425zM2 22V2h20v20zm2-2h16V4H4zm0 0V4z");
}

</style>

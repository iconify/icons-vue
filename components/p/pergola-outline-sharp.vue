<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1c1wwbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pergola-outline-sharp" /></template>
<style>
.s1c1wwbds {
  fill: currentColor;
  d: path("M3 21V2h2v2h14V2h2v19h-2V10H5v11zM5 8h14V6H5zm6 13v-3H8v-2h8v2h-3v3zM5 8V6z");
}

</style>

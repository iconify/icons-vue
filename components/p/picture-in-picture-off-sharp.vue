<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aukydqbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:picture-in-picture-off-sharp" /></template>
<style>
.aukydqbke {
  fill: currentColor;
  d: path("m20.45 23.3l-3.3-3.3H2V4h2l2 2H3.15L.65 3.5l1.425-1.425l19.8 19.8zM22 19.15L15.85 13H19V7h-8v1.15L6.85 4H22z");
}

</style>

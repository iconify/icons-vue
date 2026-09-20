<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dks6h1wwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:videocam-off-sharp" /></template>
<style>
.dks6h1wwz {
  fill: currentColor;
  d: path("m22 17.5l-4-4v1.675L6.825 4H18v6.5l4-4zm-1.45 5.85L.65 3.45l1.4-1.4l19.9 19.9zM4 4l14 14v2H2V4z");
}

</style>

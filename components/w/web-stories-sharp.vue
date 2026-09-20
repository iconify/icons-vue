<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iflytvbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:web-stories-sharp" /></template>
<style>
.iflytvbnd {
  fill: currentColor;
  d: path("M17 20V4h2v16zM2 22V2h13v20zm19-4V6h1.5v12z");
}

</style>

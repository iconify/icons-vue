<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="tl-kidj4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:subtract-square" /></template>
<style>
.tl-kidj4s {
  fill: currentColor;
  d: path("M224 160V96a8 8 0 0 0-8-8h-48V40a8 8 0 0 0-8-8H40a8 8 0 0 0-8 8v120a8 8 0 0 0 8 8h48v48a8 8 0 0 0 8 8h120a8 8 0 0 0 8-8zm-60.69 48l-40-40h33.38l40 40Zm4.69-51.31v-33.38l40 40v33.38Zm40-16L171.31 104H208ZM48 48h104v104H48Zm56 123.31L140.69 208H104Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjfbkjutw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:north-west-sharp" /></template>
<style>
.zjfbkjutw {
  fill: currentColor;
  d: path("M18.292 19L7 7.708V15H6V6h9v1H7.708L19 18.292z");
}

</style>

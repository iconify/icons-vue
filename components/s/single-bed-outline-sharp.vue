<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya9d7nbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:single-bed-outline-sharp" /></template>
<style>
.ya9d7nbcp {
  fill: currentColor;
  d: path("M6.77 18h-.54l-.38-2H5v-5h2V7h10v4h2v5h-.85l-.38 2h-.54l-.38-2h-9.7zm5.73-7H16V8h-3.5zM8 11h3.5V8H8zm-2 4h12v-3H6zm12 0H6z");
}

</style>

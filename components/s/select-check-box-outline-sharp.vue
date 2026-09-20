<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-efj7chr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:select-check-box-outline-sharp" /></template>
<style>
.e-efj7chr {
  fill: currentColor;
  d: path("M4 20V4h15.606l-1 1H5v14h14v-7.361l1-1V20zm7.525-3.712l-4.554-4.553l.708-.708l3.865 3.865l8.79-8.79l.695.683z");
}

</style>

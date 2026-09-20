<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8b_si4rf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:video-library-outline-sharp" /></template>
<style>
.d8b_si4rf {
  fill: currentColor;
  d: path("m11.5 14.5l7-4.5l-7-4.5zM6 18V2h16v16zm2-2h12V4H8zm-6 6V6h2v14h14v2zM8 4v12z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afefymbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:repeat-outline-sharp" /></template>
<style>
.afefymbrh {
  fill: currentColor;
  d: path("m7 22l-4-4l4-4l1.4 1.45L6.85 17H17v-4h2v6H6.85l1.55 1.55zM5 11V5h12.15L15.6 3.45L17 2l4 4l-4 4l-1.4-1.45L17.15 7H7v4z");
}

</style>

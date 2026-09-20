<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us7v9qbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tilt-arrow-up-sharp" /></template>
<style>
.us7v9qbqs {
  fill: currentColor;
  d: path("M2 21L6 3h12l4 18zm9-9.175V16h2v-4.175l1.6 1.575L16 12l-4-4l-4 4l1.4 1.425z");
}

</style>

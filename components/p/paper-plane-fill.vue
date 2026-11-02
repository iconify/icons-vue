<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je9z8f8sr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paper-plane-fill" /></template>
<style>
.je9z8f8sr {
  fill: currentColor;
  d: path("M17.684 3.051a2.582 2.582 0 0 1 3.265 3.265l-4 12a3.2 3.2 0 0 1-.609 1.066c-.506.584-1.28 1.041-2.077.917a1.56 1.56 0 0 1-1.157-.852l-2.38-4.759l3.981-3.981a.999.999 0 1 0-1.414-1.414l-3.981 3.981l-4.759-2.38a1.56 1.56 0 0 1-.852-1.157c-.124-.797.333-1.571.917-2.077a3.2 3.2 0 0 1 1.066-.609Z");
}

</style>

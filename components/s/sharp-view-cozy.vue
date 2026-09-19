<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajvpkp0ft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-view-cozy" /></template>
<style>
.ajvpkp0ft {
  fill: currentColor;
  d: path("M22 4H2v16h20zM11.25 16.75h-4v-4h4zm0-5.5h-4v-4h4zm5.5 5.5h-4v-4h4zm0-5.5h-4v-4h4z");
}

</style>

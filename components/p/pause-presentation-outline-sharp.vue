<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-17n8sfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pause-presentation-outline-sharp" /></template>
<style>
.m-17n8sfd {
  fill: currentColor;
  d: path("M9 16h2V8H9zm4 0h2V8h-2zM2 20V4h20v16zm2-2h16V6H4zm0 0V6z");
}

</style>

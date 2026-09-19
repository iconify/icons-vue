<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vx5nyhbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:privacyidea-authenticator" /></template>
<style>
.vx5nyhbzs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.736 5.977S20.033 9.016 23.73 9.09c3.92.08 17.534-3.59 17.534-3.59M6.736 17.67h34.528l-.382 15c-.689 13.875-33.414 12.205-33.732.349z");
}

</style>

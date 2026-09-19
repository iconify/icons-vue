<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kpnhbe7zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:walmart" /></template>
<style>
.kpnhbe7zl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 15.42V4.5m7.41 15.2l9.46-5.46m-9.46 14.02l9.46 5.46M24 32.58V43.5m-7.41-15.24l-9.46 5.46m9.46-14.02l-9.46-5.46");
}

</style>

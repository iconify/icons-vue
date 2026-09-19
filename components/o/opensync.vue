<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v3bynsbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:opensync" /></template>
<style>
.v3bynsbhg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.711 29.711a8.077 8.077 0 1 0 0-11.422L18.29 29.71a8.077 8.077 0 1 1 0-11.422");
}

</style>

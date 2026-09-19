<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="shw-yjb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:namma-yatri" /></template>
<style>
.shw-yjb5w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m7.055 5.55l.048 14.402C7.055 16.057 13.897 5.566 23.45 5.5c9.553-.065 17.368 9.069 17.495 14.452m-.191 22.532V27.965c0 4.767-7.343 14.663-16.85 14.534c-9.506-.13-16.775-9.023-16.8-14.534");
}

</style>

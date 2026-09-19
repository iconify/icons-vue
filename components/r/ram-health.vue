<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j2czhfm1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ram-health" /></template>
<style>
.j2czhfm1i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 21.352v11.15m-5.575-5.575h11.15M28.1 34.844h6.635c4.617 0 2.58-3.555 1.714-5.092L23.992 7.647L11.535 29.752c-.865 1.537-2.903 5.092 1.714 5.092h6.635M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24");
}

</style>

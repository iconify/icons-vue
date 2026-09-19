<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ltsf8fbft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nofasel" /></template>
<style>
.ltsf8fbft {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 38.414V9.586l19.099 28.828V9.586M28.086 24h9.369m-9.369 14.414V9.586H42.5");
}

</style>

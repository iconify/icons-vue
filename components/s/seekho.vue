<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h-0o86bxs"/><path class="xotlkxbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:seekho" /></template>
<style>
.h-0o86bxs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.091 3.5c4.478 4.815.337 9.722.337 9.722l-8.035 7.882l5.643 5.704l-5.06 4.999L9.334 21.165z");
}

.xotlkxbcz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.909 44.5c-4.478-4.815-.337-9.722-.337-9.722l8.035-7.882l-5.643-5.704l5.06-4.999l10.642 10.642z");
}

</style>

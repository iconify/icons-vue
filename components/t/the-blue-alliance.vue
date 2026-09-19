<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f1tr67kpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:the-blue-alliance" /></template>
<style>
.f1tr67kpt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.055 14.66v19.895m17.89-19.895v19.895m-17.89 0A8.945 8.945 0 0 0 24 43.5h0m8.945-8.945A8.945 8.945 0 0 1 24 43.5m0-28.824V43.5m-8.945-10.018h17.89m-17.89-10.019h17.89M12.55 4.5h22.9c.793 0 1.43.638 1.43 1.431v7.156c0 .793-.638 1.431-1.43 1.431h-22.9a1.43 1.43 0 0 1-1.43-1.43V5.93c0-.793.638-1.431 1.43-1.431");
}

</style>

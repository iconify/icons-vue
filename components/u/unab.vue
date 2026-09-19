<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="tcn_94byt"/><path class="eproapr6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:unab" /></template>
<style>
.eproapr6m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.444 36.78l-4.02 2.97l-.018 3.75m27.15-6.72l4.02 2.97l.018 3.75M14.409 17.953h4.737v10.845h-4.737zm14.444 0h4.737v10.845h-4.737zm-2.483 0l-2.354-2.385l-2.385 2.385V28.8h4.738Z");
}

.tcn_94byt {
  cx: 24px;
  cy: 23.178px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 16.871px;
  ry: 18.678px;
}

</style>

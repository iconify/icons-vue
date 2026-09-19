<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x5dn6butq"/><path class="n00ybpbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:photo-and-picture-resizer" /></template>
<style>
.n00ybpbrx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.847 20.465v10.749l10.708-10.749M15.847 31.214h10.368M32.683 5.5H42.5L31.387 15.633m11.113-.122V5.5");
}

.x5dn6butq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.741 25.369V42.5H5.5l.049-34.262h14.393");
}

</style>

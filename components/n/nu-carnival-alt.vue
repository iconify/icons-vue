<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dfhqr2b2w"/><path class="r5m7pjbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nu-carnival-alt" /></template>
<style>
.dfhqr2b2w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.878 36.282l2.608-5.14L28.17 9.48L22.003 4.5l-3.4 5.218l2.53 21.345z");
}

.r5m7pjbka {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.604 9.718l4.94 18.421L28.17 9.48m-4.625 18.659l2.333 8.143m-10.846-5.428l-6.24 1.074m7.353 1.862l-5.061 2.741m8.211.686L15.27 39.83m6.92-.619l-1.408 2.8m5.19-2.379l.113 3.868m4.701-4.942l3.346 3.914m-1.061-7.423l4.49 3.668m-4.339-7.263l5.986.704");
}

</style>

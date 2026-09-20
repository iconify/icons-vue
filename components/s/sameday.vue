<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l531hylii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sameday" /></template>
<style>
.l531hylii {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.28 36.679l6.605-22.411m.024.021L24 26.103l2.09-11.814m.025-.021l6.604 22.41m.91-29.132l7.568 23.051m0 0L27.545 12.945M14.371 7.546L6.804 30.597m0 0l13.652-17.652m-8.878-7.88L4 28.585l20 14.35l20-14.35l-7.577-23.52zm24.846 0L24 16.155L11.576 5.066M14.11 21.15l3.116 8.93h13.55l3.115-8.93");
}

</style>

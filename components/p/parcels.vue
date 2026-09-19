<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yoo9esmnk"/><path class="e0be65-2d"/><path class="ckroitd1l"/><path class="t6e5kzegf"/><path class="j0ui-tbke"/><path class="mblcahcha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:parcels" /></template>
<style>
.ckroitd1l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.587 30.27l3.103 1.792L24 26.687l-9.31-5.375l-9.31 5.375l3.104 1.792M24 15.938v10.75m-9.31-16.125v10.75m18.62-10.75v10.75m-12.413-2.145v-5.022l9.31-5.375l-3.104-1.791l-9.31 5.375v5.02l1.395-.615z");
}

.e0be65-2d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.587 35.293V30.27l9.31-5.375l-3.104-1.791l-9.31 5.375v5.02l1.395-.615z");
}

.j0ui-tbke {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.207 35.293V30.27l9.31-5.375l-3.104-1.791l-9.31 5.375v5.02l1.395-.615z");
}

.mblcahcha {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.207 30.27l3.103 1.792l9.31-5.375l-9.31-5.375L24 26.687l3.104 1.792m7.969 10.987L39.5 36.91m-4.427.445l3.139-1.813");
}

.t6e5kzegf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.897 14.146L24 15.937l9.31-5.375L24 5.187l-9.31 5.375l3.104 1.792M24 37.438l9.31 5.375l9.31-5.375v-10.75m-9.31 5.375v10.75");
}

.yoo9esmnk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.38 26.688v10.75l9.31 5.375L24 37.438v-10.75m-9.31 5.375v10.75");
}

</style>

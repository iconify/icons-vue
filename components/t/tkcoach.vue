<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tb0whz-6g"/><path class="j34_7acyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tkcoach" /></template>
<style>
.j34_7acyy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.327 30.494h9.178v3.063h-2.832v4.463H9.159v-4.463H6.327zm8.526-21.798s1.746 5.8 10.755 9.76c0 0 7.07 4.68.1 17.127M41.673 5.502s.14 3.38-6.337 10.351c0 0 9.576 6.126-2.042 19.998M30.646 7.959c1.649 2.31 1.523 5.227-.28 6.515c-1.805 1.288-4.604.459-6.254-1.852s-1.523-5.227.28-6.515c1.805-1.288 4.604-.459 6.254 1.852");
}

.tb0whz-6g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.076 33.545h4.341l-4.403 4.475l4.403 4.48h-4.341l-4.403-4.48z");
}

</style>

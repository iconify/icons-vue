<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wrz6btrdz"/><path class="we91-1b2s"/><path class="r81qvjtya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:naver-prism" /></template>
<style>
.r81qvjtya {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 6.629l19 34.743H5z");
}

.we91-1b2s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 12.415l14.299 26.242H9.7z");
}

.wrz6btrdz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 18.213l9.652 17.545H14.348z");
}

</style>

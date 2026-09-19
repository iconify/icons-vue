<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o3yvlublj"/><path class="i6ittvbqb"/><path class="fozqmbbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qnb-finansbank" /></template>
<style>
.fozqmbbmk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.239 8.56l11.427 11.427L35.093 8.56m7.072 15.106H27.343M38.77 12.239L27.343 23.666L38.77 35.093m-15.106 7.072V27.343M35.091 38.77L23.664 27.343L12.237 38.77M5.165 23.664h14.822M8.56 35.091l11.427-11.427L8.56 12.237");
}

.i6ittvbqb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.239 8.56l11.427 11.427L35.093 8.56M23.666 5.165v14.822");
}

.o3yvlublj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.666 5.165v14.822M12.239 8.56l11.427 11.427L35.093 8.56M23.666 5.165v14.822");
}

</style>

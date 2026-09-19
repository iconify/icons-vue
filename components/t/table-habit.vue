<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="akcvedbgi"/><path class="wkrf_3bde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:table-habit" /></template>
<style>
.akcvedbgi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.422 5.5h11.354v30.743L9.422 42.5zm19.13 0H39.94v17.34l-11.388 6.303z");
}

.wkrf_3bde {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.492 17.046H9.59l-1.148-.856l-1.823.99l2.802 7h23.237zm2.329 13.998c3.072 0 5.56 2.499 5.56 5.582s-2.488 5.593-5.56 5.593s-5.559-2.51-5.559-5.593s2.487-5.582 5.56-5.582");
}

</style>

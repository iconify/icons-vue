<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xgjypfi6d"/><path class="c64_oxgwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:street-measure" /></template>
<style>
.c64_oxgwr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.813 22.141H38.96v6.997H13.813zM42.5 11.571l-6.117 10.57m-4.049 6.997L24.602 42.5m-7.139-6.92l-2.443 4.221m6.17-10.663l-1.205 2.197m5.255-9.195l2.028-3.504m4.972-8.592l-2.37 4.348m0 7.748v4.852m3.296-4.852v1.746m3.294-1.746v4.852m-9.884-4.852v1.746M23.28 22.14v4.852m-3.295-4.852v1.746M16.69 22.14l-.05 4.852M34.948 5.545l-.554.957");
}

.xgjypfi6d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-15.073 0L5.5 36.478");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="u_u9u_b6m"/><path class="fw0ppnbex"/><path class="k-xqiwbqo"/><path class="zwiw2-bkv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:streets-map-point-broken" /></template>
<style>
.fw0ppnbex {
  d: path("M14.0004 13.9998L20.5004 20.4998M16 12.0003L14.0004 13.9998L6.39453 21.6057M21.6072 6.39307L19 9.00027");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k-xqiwbqo {
  d: path("M2 12C2 16.714 2 19.0711 3.46447 20.5355C4.92893 22 7.28595 22 12 22C16.714 22 19.0711 22 20.5355 20.5355C22 19.0711 22 16.714 22 12C22 7.28595 22 4.92893 20.5355 3.46447C19.0711 2 16.714 2 12 2C7.28595 2 4.92893 2 3.46447 3.46447C2.49073 4.43821 2.16444 5.80655 2.0551 8");
}

.u_u9u_b6m {
  d: path("M5.5 8.7572C5.5 6.95823 7.067 5.49988 9 5.49988C10.933 5.49988 12.5 6.95823 12.5 8.7572C12.5 10.5421 11.3829 12.6248 9.64003 13.3697C9.23374 13.5433 8.76626 13.5433 8.35997 13.3697C6.61708 12.6248 5.5 10.5421 5.5 8.7572Z");
}

.zwiw2-bkv {
  stroke-linejoin: round;
  d: path("M9 9H9.0001");
}

</style>

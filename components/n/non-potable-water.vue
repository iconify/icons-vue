<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="uv2k_cc_c"/><path class="njmnlnvjm"/><g class="n1mjunbsu"><path class="j1__kpbtn"/><path class="gg0sv7wac"/></g><path class="vgy2k6blz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:non-potable-water" /></template>
<style>
.gg0sv7wac {
  d: path("M16 5h-2a1 1 0 0 0 0 2h2a1 1 0 0 0 0-2m4 2h2a1 1 0 1 0 0-2h-2a1 1 0 1 0 0 2");
}

.j1__kpbtn {
  d: path("M28 10h-9V5s0-1-1-1s-1 1-1 1v5c-6 0-6 6-6 6v1c0 1 1 1 1 1h2s1 0 1-1v-1c0-2 2-2 2-2h11c1 0 1-1 1-1v-2s0-1-1-1");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.njmnlnvjm {
  fill: var(--svg-color--fff, #fff);
  d: path("M17 19c-1 0-1 1-1 1v4h-6v-4s-.021-1-1.021-1S8 20 8 20v8s0 2 2 2h6c2 0 2-2 2-2v-8s0-1-1-1");
}

.uv2k_cc_c {
  d: path("M34.999 17.999c0 9.389-7.611 17-17 17S1 27.388 1 17.999S8.61 1 17.999 1s17 7.61 17 16.999");
}

.vgy2k6blz {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M18 0C8.059 0 0 8.06 0 18c0 9.941 8.059 18 18 18s18-8.059 18-18c0-9.94-8.059-18-18-18m16 18c0 3.968-1.453 7.591-3.845 10.388L7.612 5.845A15.93 15.93 0 0 1 18 2c8.837 0 16 7.164 16 16M2 18c0-3.968 1.453-7.592 3.845-10.388l22.543 22.544A15.92 15.92 0 0 1 18 34C9.164 34 2 26.837 2 18");
}

</style>

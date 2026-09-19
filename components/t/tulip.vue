<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="kt-fw5bbz"/><path class="uipqikb9g"/><path class="dljew7bai"/><path class="jsch2eb5a"/><path class="u-4_tfbda"/><path class="d2-o2fhgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:tulip" /></template>
<style>
.d2-o2fhgf {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M24.8 43.1c6.6 6.6 8.7 20.9 8.7 20.9h-4.8C21 45.8 2 32.5 2 32.5s16.2 4.1 22.8 10.6");
}

.dljew7bai {
  fill: var(--svg-color--aa1f65, #aa1f65);
  d: path("M45.2 25.1c0 11-5.2 15.7-11.6 15.7S22 36.1 22 25.1S33.6 1 33.6 1s11.6 13.1 11.6 24.1");
}

.jsch2eb5a {
  fill: var(--svg-color--d33777, #d33777);
  d: path("M37 19.9c14.8 9.3 4.8 22.5-3.6 22.5s-15.2-8.6-15.2-19.3s8.3-19.3 8.3-19.3s-.4 9.3 10.5 16.1");
}

.kt-fw5bbz {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M39.8 45.1C33.4 50.4 33.9 64 33.9 64h2.2C41.9 46.2 62 39.5 62 39.5s-12.8-2.3-22.2 5.6");
}

.u-4_tfbda {
  fill: var(--svg-color--e84d88, #e84d88);
  d: path("M30.3 19.9c-14.8 9.3-4.8 22.5 3.6 22.5s15.2-8.6 15.2-19.3s-8.2-19.2-8.2-19.2s.3 9.2-10.6 16");
}

.uipqikb9g {
  fill: var(--svg-color--75a843, #75a843);
  d: path("m33.6 1l2.5 63h-5z");
}

</style>

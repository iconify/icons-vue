<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd3g2p-cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:split-scene-left-rounded" /></template>
<style>
.kd3g2p-cj {
  fill: currentColor;
  d: path("M15.385 19q-.214 0-.357-.143q-.144-.143-.144-.357v-13q0-.213.144-.357q.143-.143.357-.143h3q.69 0 1.153.463T20 6.616v10.769q0 .69-.462 1.153T18.384 19zm-3.742 1.857q-.143-.143-.143-.357V19H5.616q-.691 0-1.153-.462T4 17.384V6.616q0-.691.463-1.153T5.616 5H11.5V3.5q0-.213.143-.357T12 3t.357.143t.143.357v17q0 .214-.143.357T12 21t-.357-.143");
}

</style>

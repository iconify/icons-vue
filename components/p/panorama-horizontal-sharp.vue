<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdkiawb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:panorama-horizontal-sharp" /></template>
<style>
.pdkiawb1m {
  fill: currentColor;
  d: path("M3.006 19V5.033q1.99.644 4.144 1.075t4.856.43t4.856-.43t4.144-1.075V19q-1.99-.644-4.144-1.053t-4.856-.409t-4.856.409T3.006 19");
}

</style>

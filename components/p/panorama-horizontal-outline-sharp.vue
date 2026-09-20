<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hk8rcy2eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:panorama-horizontal-outline-sharp" /></template>
<style>
.hk8rcy2eq {
  fill: currentColor;
  d: path("M4 17.65q1.95-.575 3.963-.862T12 16.5t4.038.288T20 17.65V6.394q-1.95.575-3.963.84Q14.026 7.5 12 7.5t-4.038-.265T4 6.395zM3.006 19V5.033q1.99.644 4.144 1.075t4.856.43t4.856-.43t4.144-1.075V19q-1.99-.644-4.144-1.053t-4.856-.409t-4.856.409T3.006 19M12 12.02");
}

</style>

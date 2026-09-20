<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz119rb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:query-stats-outline-sharp" /></template>
<style>
.zz119rb6j {
  fill: currentColor;
  d: path("M2.817 13.256L2 12.677L6.25 5.85l2.885 3.385l3.807-6.212l2.885 4.346L19.183 2l.778.598l-4.123 6.6l-2.86-4.321l-3.703 6.04l-2.89-3.39zM14.116 18q1.203 0 2.034-.831t.83-2.035t-.83-2.034t-2.035-.83t-2.034.83t-.831 2.035t.831 2.034t2.035.831m5.157 3l-2.815-2.815q-.487.388-1.08.602T14.115 19q-1.61 0-2.737-1.126q-1.128-1.127-1.128-2.736t1.127-2.739t2.735-1.13t2.739 1.128t1.13 2.737q0 .67-.214 1.273q-.213.602-.601 1.09l2.796 2.815z");
}

</style>

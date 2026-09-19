<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ljtc0kwmb"/><path class="wu3_3qqte"/><circle class="acxvmkbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:matlab" /></template>
<style>
.acxvmkbyz {
  cx: 41.993px;
  cy: 35.989px;
  r: 0.75px;
  fill: currentColor;
}

.ljtc0kwmb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.9 31.519c4.02-1.983 4.796 2.997 7.705 8.68c.1.197.321.307.536.253c7.539-1.893 10.655-18.92 20.852-4.463c-3.973-7.238-9.012-28.455-12.418-28.455c-2.88 0-4.33 9.971-9.51 17.477M12.9 31.519c3.013-1.487 5.324-3.842 7.164-6.508M12.9 31.519l-7.183-5.002a.507.507 0 0 1 .098-.885l9.312-3.801a.5.5 0 0 1 .483.054l4.455 3.126");
}

.wu3_3qqte {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.383 21.726s1.541-3.233 4.542-4.115c2.412-.71 3.76-2.98 3.76-2.98l3.69-5.039");
}

</style>

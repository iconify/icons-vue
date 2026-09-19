<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lnxitkb2r"/><circle class="pmusaxosd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mp3-snijder-and-beltoon-maker" /></template>
<style>
.lnxitkb2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.72 8.881h2.552c1.87 0 2.375-1.33 2.193-2.908H37.72v9.617m0 .273a2.753 2.753 0 1 1-5.506 0a2.753 2.753 0 0 1 5.506 0M9.168 22.674a2.545 2.545 0 1 0 3.284 3.888a2.545 2.545 0 0 0-3.284-3.888m5.698-1.482a5.31 5.31 0 1 0-.63 7.482h0a5.23 5.23 0 0 0 1.757-2.956l3.9-.009c.453 0 .945.205 1.24.554s.415.868.34 1.314l-.661 3.845a5.23 5.23 0 0 0-3.208 1.237a5.31 5.31 0 1 0 6.852 8.112h0a5.31 5.31 0 0 0 .63-7.482a5.2 5.2 0 0 0-1.728-1.34l.696-4.077l13.609-1.18c1.78-.154 3.625-2.004 4.534-3.612l-17.329.028l2.922-17.08c-1.737.627-3.87 2.137-4.32 3.867l-3.435 13.22l-4.136.006a5.2 5.2 0 0 0-1.033-1.93Zm7.807 17.466a2.545 2.545 0 1 1-3.3-3.876l.015-.011a2.545 2.545 0 0 1 3.285 3.888");
}

.pmusaxosd {
  cx: 23.099px;
  cy: 24.688px;
  r: 0.75px;
  fill: currentColor;
}

</style>

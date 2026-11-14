<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bfaq-0beq"/><path class="xy4k13b2t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-cold-warning" /></template>
<style>
.bfaq-0beq {
  d: path("M12.449 19.5H3V10l7.5-6.5L18 10v2.051");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xy4k13b2t {
  d: path("M7.5 19.5v-4q0-.123.012-.245t.036-.243q.024-.12.06-.238t.082-.231t.105-.221t.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165t.197-.146t.211-.126t.221-.105q.114-.047.231-.082t.238-.06q.121-.024.243-.036T10 13t.245.012t.243.036q.12.024.238.06t.231.082q.113.047.221.105q.109.058.211.126q.102.069.197.146q.095.078.182.165t.165.182t.146.197t.126.211t.105.221q.047.114.082.231t.06.238q.024.121.036.243t.012.245v.246m2.75 2.754h6.5m-4.875-2.815l3.25 5.63m0-5.63l-3.25 5.63");
}

</style>

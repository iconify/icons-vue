<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="pv1oyibvi"/><path class="jnrc1zgbs"/><path class="rdqjq3_3j"/><path class="reqhcjw1d"/><path class="wnqbup91m"/></g><path class="xm9uzjeuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smzdm" /></template>
<style>
.jnrc1zgbs {
  d: path("M13.047 20.106c2.162 3.614 1.907 10.381 2.861 17.205m2.639-11.869c1.475 1.564 1.438 5.72 2.013 10.854c6.705-2.166 15.216-4.023 18.588-4.242M18.99 15.637c5.173-.325 9.833-2.21 13.776-3.633");
}

.pv1oyibvi {
  d: path("M15.205 11.507c-.592 5.363-2.358 10.884-7.476 16.632");
}

.rdqjq3_3j {
  d: path("M25.414 9.081c.234 3.492.112 7.78-.669 10.634m-2.705.688c1.3 3.428 1.585 7.456 2.173 11.48");
}

.reqhcjw1d {
  d: path("M22.136 20.655c3.043-1.107 5.604-2.12 8.866-2.918c.001 3.169.835 6.195 2 12.415m-9.989-6.327l6.089-2.06m-5.476 5.747l6.054-1.908");
}

.wnqbup91m {
  d: path("M24.161 31.498c4.136-1.546 6.696-2.033 8.4-2.47");
}

.xm9uzjeuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j5ii9b_gd"/><path class="ms-gg3bwx"/><ellipse class="pnpaj7b6f"/><path class="cwx4dqbaq"/><circle class="r1wnnobvi"/><circle class="kay_p0bel"/><path class="loxmj_btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ollama" /></template>
<style>
.cwx4dqbaq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 26.987v1.087m0-1.087l.917-.917m-.917.917l-.917-.917");
}

.j5ii9b_gd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.125 42.5c-.68-2.589-.258-5.178.971-7.767c-2.259-2.467-2.127-6.929 0-9.376c-3.78-4.258-2.17-11.787 4.754-11.766c1.511-1.973 3.704-3.622 6.15-3.725");
}

.kay_p0bel {
  cx: 30.795px;
  cy: 21.008px;
  r: 0.75px;
  fill: currentColor;
}

.loxmj_btc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.875 42.5c.68-2.589.258-5.178-.971-7.767c2.259-2.467 2.127-6.929 0-9.376c3.78-4.258 2.17-11.787-4.754-11.766c-1.511-1.973-3.704-3.622-6.15-3.725");
}

.ms-gg3bwx {
  fill: none;
  stroke: currentColor;
  d: path("M19.303 12.006c0-4.65-1.428-6.506-3.184-6.506s-2.315 5.607-1.699 8.823m14.277-2.317c0-4.65 1.428-6.506 3.184-6.506s2.315 5.607 1.699 8.823");
}

.pnpaj7b6f {
  cx: 24px;
  cy: 26.987px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.892px;
  ry: 3.805px;
}

.r1wnnobvi {
  cx: 17.205px;
  cy: 21.008px;
  r: 0.75px;
  fill: currentColor;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="wl1w-ac_k"/><path class="ohq2ojbmt"/><path class="l5rvwo-bx"/><circle class="tcppgqbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-friend-pedro" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l5rvwo-bx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.688 29.336c.76.245 1.52.49 2.692.595s2.753.067 4.372-.209s3.274-.79 4.93-1.306");
}

.ohq2ojbmt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.203 42.297c.786-1.398 1.571-2.795 2.05-4.118s.653-2.572.818-4.072s.32-3.252.32-4.709s-.155-2.619-.38-3.92c-.226-1.3-.521-2.74-.583-4.275s.11-3.167.514-4.339c.405-1.171 1.042-1.883 1.27-2.603c.226-.72.042-1.45-.2-2.036c-.242-.585-.543-1.027-.868-1.324s-.674-.45-.98-.886c-.307-.435-.57-1.153-.697-1.671c-.125-.518-.113-.837-.021-1.082s.264-.417.987-.512s1.999-.114 2.76-.092c.76.021 1.005.083 1.18.178c.174.095.279.223.619.8s.917 1.6 1.432 2.28c.515.681.968 1.018 2.057 1.49c1.088.473 2.811 1.08 4.301 1.908s2.747 1.876 3.857 3.323s2.072 3.292 2.72 5.503c.646 2.21.977 4.786 1.287 7.56s.597 5.748.588 7.8c-.009 2.05-.316 3.179-.622 4.307");
}

.tcppgqbdm {
  cx: 19.609px;
  cy: 26.852px;
  r: 1.065px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wl1w-ac_k {
  cx: 29.087px;
  cy: 25.952px;
  r: 1.065px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

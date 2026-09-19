<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="li56cpb2v"/><path class="z5tk6mloj"/><circle class="g2rr9fz9c"/><path class="zwne9-bpx"/><path class="nm56x0bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sharp-network-print" /></template>
<style>
.g2rr9fz9c {
  cx: 24px;
  cy: 30.938px;
  r: 6.15px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.li56cpb2v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.437 24H6.5c-.554 0-1-.446-1-1V6.5c0-.554.446-1 1-1h35c.554 0 1 .446 1 1V23c0 .554-.446 1-1 1h-5.938");
}

.nm56x0bmo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.283 35.33c-1.26-.84-2.766-1.318-4.283-1.318s-3.021.479-4.282 1.319m8.565-8.787c-1.26.84-2.766 1.318-4.283 1.318s-3.021-.478-4.282-1.318");
}

.z5tk6mloj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.438 19.375V40.5c0 1.108.892 2 2 2h15v-4.125c0-1.108.892-2 2-2h4.125v-17zM5.5 14.75h37m-6.938 21.626L29.437 42.5m-2.465-30.177V7.86l-2.466 2.997h3.044m-7.1-1.517c0-.913.851-1.632 1.825-1.45c.638.119 1.148.655 1.212 1.283c.047.467-.105.928-.438 1.211c-.616.525-2.599 1.94-2.599 1.94h3.045");
}

.zwne9-bpx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 24.788v12.3m-6.15-6.15h12.3m-3.075 0c0-2.376-1.174-4.724-3.075-6.15c-1.9 1.425-3.075 3.774-3.075 6.15S22.1 35.662 24 37.088c1.901-1.426 3.075-3.774 3.075-6.15");
}

</style>

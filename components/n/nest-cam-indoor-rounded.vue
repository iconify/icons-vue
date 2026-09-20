<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uds-nts4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-cam-indoor-rounded" /></template>
<style>
.uds-nts4x {
  fill: currentColor;
  d: path("M10.991 10.447q-.414-.418-.414-1.005t.414-1.005T12 8.02t1.009.415t.414 1.008t-.414 1.009t-1.009.415t-1.009-.419M7.731 20.52q0-.402.299-.7t.7-.3h2.77q0-1.536-.742-2.864q-.742-1.329-2.031-2.19q-1.27-.84-1.998-2.168Q6 10.968 6 9.447q0-2.506 1.745-4.256q1.746-1.749 4.251-1.749t4.255 1.749T18 9.448q0 1.544-.725 2.883t-2.033 2.16q-1.306.811-2.024 2.151T12.5 19.52h2.77q.404 0 .692.3q.288.298.288.7zm7.807-7.54Q17 11.518 17 9.443t-1.463-3.537T12 4.442T8.463 5.905T7 9.442t1.463 3.538T12 14.442t3.538-1.462");
}

</style>

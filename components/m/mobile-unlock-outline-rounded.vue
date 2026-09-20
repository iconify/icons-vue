<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2m3dfbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-unlock-outline-rounded" /></template>
<style>
.v2m3dfbam {
  fill: currentColor;
  d: path("M9.923 15.385h3.385q.367 0 .607-.24q.239-.24.239-.606V12q0-.367-.24-.607q-.239-.24-.606-.24h-.423v-.845q0-.367.239-.607t.607-.24t.645.24t.278.607v.461q0 .162.112.273q.111.112.273.112t.273-.112t.111-.273v-.461q0-.69-.501-1.153q-.5-.463-1.191-.463q-.671 0-1.143.472t-.472 1.144v.846H9.923q-.367 0-.607.24q-.239.239-.239.606v2.538q0 .368.24.607q.239.24.606.24M7.616 22q-.672 0-1.144-.472T6 20.385V3.615q0-.69.463-1.152T7.616 2h8.846q.67 0 1.143.472q.472.472.472 1.144V6.83q.373.04.648.31q.275.269.275.648v1.769q0 .379-.275.648t-.648.31v9.869q0 .67-.472 1.143q-.472.472-1.143.472zm0-1h8.846q.269 0 .442-.173t.173-.442V3.615q0-.269-.173-.442T16.462 3H7.616q-.27 0-.443.173T7 3.616v16.769q0 .269.173.442t.443.173M7 21V3z");
}

</style>

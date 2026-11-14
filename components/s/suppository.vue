<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wh3g8bc4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:suppository" /></template>
<style>
.wh3g8bc4t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.511 13.62l-1.8 1.858q-.051.053-.09.114q-.04.061-.067.129t-.041.14t-.013.145t.015.145t.043.139t.069.128t.093.112l4.75 4.75q.051.052.112.093t.128.069t.139.043q.072.014.145.015t.145-.013t.14-.041t.129-.067q.061-.039.114-.09l1.858-1.8q-.065.011-.13.011q-.149 0-.287-.057t-.243-.163l-5-5q-.106-.105-.163-.243T4.5 13.75q0-.065.011-.13m.586-.604q.091-.019.184-.015q.094.004.183.03q.09.027.17.075t.146.114l5 5q.066.066.114.146t.075.17q.026.089.03.183q.004.093-.015.184l5.538-5.364l.029-.03q2.34-2.535 2.98-4.668q.707-2.359-.749-3.623q-1.264-1.456-3.623-.749q-2.133.64-4.668 2.98l-.03.029z");
}

</style>

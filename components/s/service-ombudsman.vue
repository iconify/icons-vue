<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mougj5s4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:service-ombudsman" /></template>
<style>
.mougj5s4a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m5.433 9.324l3.891-3.89q1.767-1.766 3.534-.001l.708.709q1.766 1.767.001 3.534l-1.415 1.415l7.878 7.879q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-7.879-7.878l-1.415 1.414q-1.767 1.766-3.534.001l-.708-.709q-1.766-1.767-.001-3.534M4.25 17.25h5.5q2.5 0 2.5 2.5q0 1.036-.732 1.768t-1.768.732h-5.5q-1.036 0-1.768-.732T1.75 19.75q0-2.5 2.5-2.5");
}

</style>

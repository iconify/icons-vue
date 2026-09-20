<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0p9ujx7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:satellite-outline-sharp" /></template>
<style>
.e0p9ujx7a {
  fill: currentColor;
  d: path("M7.5 16.5h9.154l-2.827-3.77l-2.615 3.308l-1.75-2.115zm-1.115-5.423q1.846-.212 3.163-1.529q1.318-1.317 1.529-3.164h-.93q-.213 1.474-1.25 2.512q-1.04 1.038-2.512 1.25zm0-2.9q.69-.115 1.178-.609t.603-1.184H6.384zM4 20V4h16v16zm1-1h14V5H5zm0 0V5z");
}

</style>

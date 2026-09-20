<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ups7hacbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pivot-table-chart-outline" /></template>
<style>
.ups7hacbw {
  fill: currentColor;
  d: path("M10.385 7.616V4h8q.69 0 1.153.463T20 5.616v2zM5.615 20q-.69 0-1.152-.462T4 18.384v-8h3.616V20zM4 7.616v-2q0-.691.463-1.153T5.616 4h2v3.616zM12.5 21l-3.308-3.308l3.308-3.307l.708.707l-2.089 2.1h3.573q1.037 0 1.769-.731t.731-1.769v-3.584l-2.1 2.1l-.707-.708l3.307-3.308L21 12.5l-.708.708l-2.1-2.1v3.584q0 1.458-1.02 2.48q-1.022 1.02-2.48 1.02H11.12l2.089 2.1z");
}

</style>

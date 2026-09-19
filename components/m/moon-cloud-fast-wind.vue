<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/ts7f3ccvg.css';
import '../../css/s/sf9ffevpn.css';
import '../../css/e/ea2rukt_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ts7f3ccvg"/><path class="sf9ffevpn"/><path class="ea2rukt_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:moon-cloud-fast-wind" /></template>

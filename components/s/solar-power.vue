<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/l2rvtoxlz.css';
import '../../css/t/t43vemb6k.css';
import '../../css/u/u4agv6btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l2rvtoxlz"/><path class="t43vemb6k"/><path class="u4agv6btr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:solar-power" /></template>

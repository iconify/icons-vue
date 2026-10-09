<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvxin6bpa.css';
import '../../css/q/qvo2fwbpx.css';
import '../../css/i/ipvmyugcg.css';
import '../../css/l/lvh1_3beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rvxin6bpa"/><path class="qvo2fwbpx"/><path class="ipvmyugcg"/><path class="lvh1_3beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-meter-48-bold" /></template>

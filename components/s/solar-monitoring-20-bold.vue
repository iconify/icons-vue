<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhz704nam.css';
import '../../css/o/odoplnlhz.css';
import '../../css/k/kv_uf3bpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fhz704nam"/><path class="odoplnlhz"/><path class="kv_uf3bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-monitoring-20-bold" /></template>

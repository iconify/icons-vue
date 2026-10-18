<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/om_2m0e4d.css';
import '../../css/z/zhkqvsbwg.css';
import '../../css/a/axb1k_ble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="om_2m0e4d"/><path class="zhkqvsbwg"/><path class="axb1k_ble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-monitoring-48-bold" /></template>

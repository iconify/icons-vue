<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_r7mhbff.css';
import '../../css/n/nrcinobha.css';
import '../../css/r/rvdcy0bsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i_r7mhbff"/><path class="nrcinobha"/><path class="rvdcy0bsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:speedometer-48" /></template>

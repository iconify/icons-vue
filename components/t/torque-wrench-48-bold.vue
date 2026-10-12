<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7he9kybi.css';
import '../../css/r/rayd8obar.css';
import '../../css/p/pq2cdhyot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n7he9kybi"/><path class="rayd8obar"/><path class="pq2cdhyot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:torque-wrench-48-bold" /></template>

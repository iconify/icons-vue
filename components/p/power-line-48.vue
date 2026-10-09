<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbo4sbc_y.css';
import '../../css/o/oowff5lqf.css';
import '../../css/q/qs2b_84ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mbo4sbc_y"/><path class="oowff5lqf"/><path class="qs2b_84ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:power-line-48" /></template>

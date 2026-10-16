<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw2ccwbeu.css';
import '../../css/e/eyxhlubzl.css';
import '../../css/o/o25la7b3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xw2ccwbeu"/><path class="eyxhlubzl"/><path class="o25la7b3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-turbine-off-48" /></template>

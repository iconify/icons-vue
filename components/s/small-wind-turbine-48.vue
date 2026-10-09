<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygn31xzau.css';
import '../../css/x/xw5_61bwy.css';
import '../../css/q/qgrtu-b6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ygn31xzau"/><path class="xw5_61bwy"/><path class="qgrtu-b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:small-wind-turbine-48" /></template>

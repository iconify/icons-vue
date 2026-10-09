<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kecam2bme.css';
import '../../css/d/duw87ybvv.css';
import '../../css/z/zyyp67_ey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kecam2bme"/><path class="duw87ybvv"/><path class="zyyp67_ey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sprout-20-bold" /></template>

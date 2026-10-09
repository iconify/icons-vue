<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo1eldb9g.css';
import '../../css/e/e26qy--yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fo1eldb9g"/><path class="e26qy--yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-inverter-20" /></template>

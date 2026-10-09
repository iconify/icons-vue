<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixy5tybnv.css';
import '../../css/s/sypm-h04n.css';
import '../../css/r/rdsgzmbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ixy5tybnv"/><path class="sypm-h04n"/><path class="rdsgzmbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-array-sun-48-bold" /></template>

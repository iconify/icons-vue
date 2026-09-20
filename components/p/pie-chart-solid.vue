<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umbcrlb4m.css';
import '../../css/k/kmzsj98hw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="umbcrlb4m"/><path class="kmzsj98hw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:pie-chart-solid" /></template>

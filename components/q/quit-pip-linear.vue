<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/i2iiwfb2x.css';
import '../../css/x/xnh1ybbye.css';
import '../../css/m/mqszbo63g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i2iiwfb2x"/><path class="xnh1ybbye"/><path class="mqszbo63g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:quit-pip-linear" /></template>

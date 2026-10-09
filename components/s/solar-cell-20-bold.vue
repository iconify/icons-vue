<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9svkd5iy.css';
import '../../css/m/m5wg2ub_n.css';
import '../../css/l/lgigiqbja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k9svkd5iy"/><path class="m5wg2ub_n"/><path class="lgigiqbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-cell-20-bold" /></template>

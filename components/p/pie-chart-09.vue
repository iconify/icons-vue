<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr2y-vbdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr2y-vbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pie-chart-09" /></template>

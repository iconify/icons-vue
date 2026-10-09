<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyz6g2bdx.css';
import '../../css/f/fad7f9tkf.css';
import '../../css/w/wmo2g_b9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tyz6g2bdx"/><path class="fad7f9tkf"/><path class="wmo2g_b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:power-station-20-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/n9h46nbry.css';
import '../../css/v/vjwvg5ojq.css';
import '../../css/q/qiqtkwofx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="n9h46nbry"/><path class="vjwvg5ojq"/><path class="qiqtkwofx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:train" /></template>

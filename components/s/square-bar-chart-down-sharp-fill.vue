<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdr0sobjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qdr0sobjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-bar-chart-down-sharp-fill" /></template>

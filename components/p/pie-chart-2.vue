<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj27b0b7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vj27b0b7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:pie-chart-2" /></template>

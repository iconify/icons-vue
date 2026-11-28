<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjrbj5liv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjrbj5liv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:scatter-chart-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo0tzaczo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lo0tzaczo primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:scatter-chart-duotone" /></template>

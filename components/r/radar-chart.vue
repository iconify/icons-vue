<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmjuior3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmjuior3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:radar-chart" /></template>

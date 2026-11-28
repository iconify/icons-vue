<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx7svgbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cx7svgbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:thermometer" /></template>

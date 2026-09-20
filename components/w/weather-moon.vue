<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo-p5bc0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oo-p5bc0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:weather-moon" /></template>

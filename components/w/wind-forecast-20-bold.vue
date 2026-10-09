<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc3i7mufd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fc3i7mufd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-forecast-20-bold" /></template>

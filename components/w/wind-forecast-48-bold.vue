<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwhfb7nyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mwhfb7nyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-forecast-48-bold" /></template>

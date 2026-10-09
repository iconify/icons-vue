<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3w-j2vjh.css';
import '../../css/d/dsi3v5bzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d3w-j2vjh"/><path class="dsi3v5bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pin-48" /></template>

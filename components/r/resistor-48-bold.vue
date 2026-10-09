<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvpunxblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kvpunxblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:resistor-48-bold" /></template>

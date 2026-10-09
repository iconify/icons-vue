<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvhip5cnc.css';
import '../../css/y/y35w4ccky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kvhip5cnc"/><path class="y35w4ccky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:micro-inverter-20" /></template>

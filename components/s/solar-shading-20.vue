<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3ivimbut.css';
import '../../css/f/fqx9z9z0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o3ivimbut"/><path class="fqx9z9z0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-shading-20" /></template>

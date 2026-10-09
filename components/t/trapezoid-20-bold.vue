<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe2i10slb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fe2i10slb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:trapezoid-20-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfhd0ccqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":356,"height":400,"top":-15};
const content = `<path class="colorff4500 svgShape yfhd0ccqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:vedic" /></template>

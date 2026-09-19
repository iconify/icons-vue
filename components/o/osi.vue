<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mut20k02r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mut20k02r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:osi" /></template>

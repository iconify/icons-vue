<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh16486iy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="hh16486iy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:octopus" /></template>

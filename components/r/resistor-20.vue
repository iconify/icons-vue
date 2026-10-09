<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owx1prskt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="owx1prskt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:resistor-20" /></template>

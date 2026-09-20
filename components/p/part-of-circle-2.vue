<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pevnz3bgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pevnz3bgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:part-of-circle-2" /></template>

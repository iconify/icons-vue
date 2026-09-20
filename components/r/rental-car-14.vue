<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr-7drb-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="kr-7drb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:rental-car-14" /></template>

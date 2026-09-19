<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4c96bbbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="k4c96bbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:square-js" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6o0__tcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="y6o0__tcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:stethoscope" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mslrnwbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mslrnwbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:star-half-solid" /></template>

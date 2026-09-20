<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnbxl2bpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wnbxl2bpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:train-car-centerbeam" /></template>

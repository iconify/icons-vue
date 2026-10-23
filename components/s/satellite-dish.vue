<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5_ny6bfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5_ny6bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:satellite-dish" /></template>

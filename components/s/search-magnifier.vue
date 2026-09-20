<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6la11b1v.css';
import '../../css/o/okcf14hbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6la11b1v"/><path class="okcf14hbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:search-magnifier" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbz25fvgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbz25fvgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:passport-check" /></template>

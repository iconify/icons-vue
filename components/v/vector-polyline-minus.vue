<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpk7z6bhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpk7z6bhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vector-polyline-minus" /></template>

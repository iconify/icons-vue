<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qijexu2va.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qijexu2va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:volume-1" /></template>

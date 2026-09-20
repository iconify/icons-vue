<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-jl_-_hw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-jl_-_hw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:spray-image" /></template>

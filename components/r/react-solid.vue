<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6dy_r2wj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6dy_r2wj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:react-solid" /></template>

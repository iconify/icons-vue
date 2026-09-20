<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_ahcn3er.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_ahcn3er"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:text-cursor" /></template>

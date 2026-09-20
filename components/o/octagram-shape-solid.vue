<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mozawhblu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mozawhblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:octagram-shape-solid" /></template>

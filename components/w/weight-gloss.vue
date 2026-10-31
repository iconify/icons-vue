<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0y_80bxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0y_80bxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:weight-gloss" /></template>

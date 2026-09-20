<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqyjh7hii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqyjh7hii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:sliders-2" /></template>

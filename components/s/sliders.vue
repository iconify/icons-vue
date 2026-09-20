<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8qjibb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8qjibb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:sliders" /></template>

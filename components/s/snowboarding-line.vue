<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3f0m41nu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3f0m41nu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:snowboarding-line" /></template>

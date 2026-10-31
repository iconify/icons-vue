<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2zpd4s6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2zpd4s6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:mammogram-outline-24px" /></template>

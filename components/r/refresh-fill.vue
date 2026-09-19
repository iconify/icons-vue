<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8kx648wy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8kx648wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:refresh-fill" /></template>

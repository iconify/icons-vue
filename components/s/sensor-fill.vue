<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv51d6bao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fv51d6bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sensor-fill" /></template>

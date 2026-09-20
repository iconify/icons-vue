<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlk5hvfth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlk5hvfth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:trademark-line" /></template>

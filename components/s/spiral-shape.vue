<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5q3hub4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5q3hub4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:spiral-shape" /></template>

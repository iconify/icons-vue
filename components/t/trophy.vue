<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j39b2ub7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j39b2ub7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:trophy" /></template>

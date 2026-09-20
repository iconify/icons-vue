<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka7_x7bmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ka7_x7bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:projector-line" /></template>

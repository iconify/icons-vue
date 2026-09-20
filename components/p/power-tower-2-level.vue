<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7zbwhbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l7zbwhbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:power-tower-2-level" /></template>

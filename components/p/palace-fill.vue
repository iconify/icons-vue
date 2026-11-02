<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jueoms9ry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jueoms9ry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:palace-fill" /></template>

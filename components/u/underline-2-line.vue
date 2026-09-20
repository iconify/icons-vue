<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp5cnkbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp5cnkbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:underline-2-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb4-j_brm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb4-j_brm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sun-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee4x8mcav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee4x8mcav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:text-align-justify" /></template>

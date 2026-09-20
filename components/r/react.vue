<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb1djevzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tb1djevzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:react" /></template>

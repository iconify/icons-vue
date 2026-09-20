<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij1inobce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ij1inobce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pig-money-line" /></template>

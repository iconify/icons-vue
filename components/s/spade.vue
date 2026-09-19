<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohmp0hbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohmp0hbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:spade" /></template>

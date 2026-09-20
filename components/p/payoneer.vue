<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-y0yg7bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-y0yg7bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:payoneer" /></template>

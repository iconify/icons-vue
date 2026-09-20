<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb64c6bwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tb64c6bwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:un-star" /></template>

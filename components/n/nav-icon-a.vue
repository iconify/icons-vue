<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arxjvacib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":24};
const content = `<path class="arxjvacib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:nav-icon-a" /></template>

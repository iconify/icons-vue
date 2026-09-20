<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6z4ynbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f6z4ynbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:power-tower-donau-1-level" /></template>

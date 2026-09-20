<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rorr57bgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rorr57bgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-megalith" /></template>

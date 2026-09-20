<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5ehiablu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g5ehiablu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorcycle-and-ruble" /></template>

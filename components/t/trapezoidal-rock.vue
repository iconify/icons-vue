<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-4_ispbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i-4_ispbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:trapezoidal-rock" /></template>

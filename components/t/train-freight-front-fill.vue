<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7_hf7wcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r7_hf7wcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:train-freight-front-fill" /></template>

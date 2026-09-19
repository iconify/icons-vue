<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9m3lvswz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u9m3lvswz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:soil-temperature-field" /></template>

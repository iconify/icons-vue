<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez9s18yps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ez9s18yps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pricing-traditional" /></template>

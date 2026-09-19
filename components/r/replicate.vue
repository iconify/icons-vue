<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u40i7pjez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u40i7pjez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:replicate" /></template>

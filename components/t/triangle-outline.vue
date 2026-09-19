<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0zc6hbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m0zc6hbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:triangle-outline" /></template>

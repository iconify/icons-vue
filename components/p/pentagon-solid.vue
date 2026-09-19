<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5_b1pbdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d5_b1pbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pentagon-solid" /></template>

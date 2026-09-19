<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz2q2c5nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mz2q2c5nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user-simulation" /></template>

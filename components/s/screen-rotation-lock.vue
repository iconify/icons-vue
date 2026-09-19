<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2c5etzdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":488,"height":496};
const content = `<path class="t2c5etzdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:screen-rotation-lock" /></template>

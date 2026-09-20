<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbps0obhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qbps0obhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:parallelogram-tall-left" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueqp5ackf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ueqp5ackf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:partition-auto" /></template>

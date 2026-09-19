<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwfgu54tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qwfgu54tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:volume-down" /></template>

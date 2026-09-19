<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwwxpfbew.css';
import '../../css/q/q352u0pff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dwwxpfbew"/><path class="q352u0pff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:task-star" /></template>

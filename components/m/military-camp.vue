<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzo58fddj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zzo58fddj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:military-camp" /></template>

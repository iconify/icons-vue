<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbgenzbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qbgenzbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:skill-level-advanced" /></template>

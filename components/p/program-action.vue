<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yen3ajh1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yen3ajh1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:program-action" /></template>

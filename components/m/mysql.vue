<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9gsxrb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h9gsxrb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mysql" /></template>
